#### Test 55467363832a26e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/cutils-trace( 4378): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4378): ====startRecUseTime====
D/htc.customization.log.level( 4378):  is 
W/CustomizationLogLevel( 4378): Level value is invalid, use default level 2
D/CustomizationManager( 4378):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4378): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4378): Parsing tag category name = system
I/CustomizationCIDLoader( 4378): Parsing tag category name = application
I/CustomizationCIDLoader( 4378): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4378): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4378): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4378): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4378): Parsing tag category name = Settings
D/CustomizationManager( 4378):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4378):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4378): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4378): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4378): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4378): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4378
D/PMS     (  906): acquireHCC(4254f650): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4304c0e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x696990d8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1112813272
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ca12a8
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  906): acquireWL(425c07e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4389 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4389): Copying FileAsset 0x5d784c88 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4389): Binding Chromium to main looper Looper (main, tid 1) {41a7e948}
I/LibraryLoader( 4389): Expected native library version number "",actual native library version number ""
I/chromium( 4389): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4389): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44049488:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4389): 1101623504: getState(). Returning 12
D/PMS     (  906): acquireWL(42d85e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(43bc44c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(42d85e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4389): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4389): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4389):                  aa63bbd948f41d15fc72f585e
W/chromium( 4389): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4389): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4389): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4389): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4389): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4389): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4389): CordovaWebView is running on device made by: HTC
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43023ea0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/AwContents( 4389): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1269
,W/ResourceType( 4389): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4389): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac8780, mServedView=org.apache.cordova.engine.SystemWebView{41a8e3e8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4389
,W/AwContents( 4389): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +275ms
,D/PMS     (  906): releaseWL(425c07e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4389): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4389): JniHelper::setJavaVM(0x41557048), pthread_self() = 1662575040
,D/JX-Cordova( 4389): jxcore cordova android initializing
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.557MB for 64402-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.586MB for 96598-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.662MB for 144892-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.777MB for 217334-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.954MB for 325996-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 12.633MB for 733480-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 13.235MB for 1100216-byte allocation
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 14.110MB for 1650320-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 15.475MB for 2475476-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 17.493MB for 3713210-byte allocation
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/jxcore-log( 4389): Initializing JXcore engine
,W/jxcore-log( 4389): JXcore engine is ready
,W/jxcore-log( 4389): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(4254f650): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(4304c0e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4389): Platform android
W/jxcore-log( 4389): 
,W/jxcore-log( 4389): Process ARCH arm
W/jxcore-log( 4389): 
,I/jxcore-log( 4389): JXcore Cordova bridge is ready!
I/jxcore-log( 4389): 
,W/jxcore-log( 4389): JXcore engine is started
,I/chromium( 4389): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(43bc44c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(434796e0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(434796e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(44200230): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(44200230): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/jxcore-log( 4389): Toggling radios to true
I/jxcore-log( 4389): 
,D/BluetoothAdapter( 4389): enable(): BT is already enabled..!
,D/WifiManager( 4389): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
,W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1268
,W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4389, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
D/WifiManager( 4389): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4389): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): TDLS: Tear down peers
I/wpa_supplicant( 1178): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4389): Radios toggled
I/jxcore-log( 4389): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4389): Received device characteristics:
I/jxcore-log( 4389): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4389): Bluetooth name: HTC Desire 820
I/jxcore-log( 4389): Device name: HTC-HTC Desire 820
I/jxcore-log( 4389): 
I/jxcore-log( 4389): Perf Test app loaded loaded
I/jxcore-log( 4389): 
I/jxcore-log( 4389): check test folder
I/jxcore-log( 4389): 
I/jxcore-log( 4389): found test : ./testFindPeers.js
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): found test : ./testSendData.js
I/jxcore-log( 4389): 
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1178): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1178): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a1cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1178): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178,): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false,
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(43b96f20): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): Fast associate: Old scan results
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=21504 mDataStallAlarmIntent=PendingIntent{423bc3a8: PendingIntentRecord{424b7c10 android broadcastIntent}}
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4224): >>>>>WISPrService start isConnected = false<<<<<
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906):    returned true
,D/WISPrService( 4224): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false,
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  364): [NET] entry_id:5   entry:0xb78bcf98  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb78c1310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb78c1428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb78bd190  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb78c10e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb78c14f0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4224): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/PMS     (  906): acquireWL(42f3a500): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1439 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4224): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): acquireWL(42ea0458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): releaseWL(42ea0458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): acquireWL(42df4e00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1178): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1439/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(42f3a500): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  906): releaseWL(42df4e00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/Choreographer( 4389): Skipped 102 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4389): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4446 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42362858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{42495c90: PendingIntentRecord{424761f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452272000393, Int=60000
,D/PMS     (  906): releaseWL(42362858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4446): SMSBackupAgentService started
,D/SMSBackup( 4446): Checking restore status
D/SMSBackup( 4446): Restore complete
,D/SMSBackup( 4446): cancelCheckAlarm
,D/SMSBackup( 4446): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3054
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3054:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3054
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/PMS     (  906): acquireWL(4254b290): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState,
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1493/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1868/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/PMS     (  906): releaseWL(4254b290): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4278/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3838/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/NetworkMonitor( 3838): type=WIFI subType= reason=null isConnected=false
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4278/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2422/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4460 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4460): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4460): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4460): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4460): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4460): Preparing secondary program dexes.
V/DexLibLoader( 4460): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4460): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4460): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4460): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4460): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4460): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4460): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
V/DexLibLoader( 4460): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader,
V/DexLibLoader( 4460): Finished creating class loader,
V/DexLibLoader( 4460): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.,
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
V/DexLibLoader( 4460): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
V/DexLibLoader( 4460): Creating class loader
V/DexLibLoader( 4460): Finished creating class loader
,V/DexLibLoader( 4460): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4460): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4460): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1178): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1178): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
D/wpa_supplicant( 1178): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1178): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1178): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1178): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1178): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1178): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 1
I/wpa_supplicant( 1178): wpa_s->is_screen_on 1
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 1
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a1e4e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
,I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb7a1e4e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb7a1d718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a1d718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb7a1d718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22),
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (778) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-47
I/wpa_supplicant( 1178): tsf=0000000107881123
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-53
I/wpa_supplicant( 1178): tsf=0000000107881139
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
,I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-76
I/wpa_supplicant( 1178): tsf=0000000107881146
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1178): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-53
I/wpa_supplicant( 1178): tsf=0000000107881134
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-79
I/wpa_supplicant( 1178): tsf=0000000107881142
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-86,
I/wpa_supplicant( 1178): tsf=0000000107881149
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=UPC5999698
I/wpa_supplicant( 1178): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 107881123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 107881139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 107881146, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 107881134, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 107881142, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 107881149, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4460): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Connect event
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1178): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on association
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1178): EAPOL: enable timer tick
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): Get randomness: len=32 entropy=7
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
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
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/FbInjectorInitializer( 4460): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a1d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): This record is existed, only update it...
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6faab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1178):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1178): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1178): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1178): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1178): set send_ind_to_ndc = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1178): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1178): EAPOL authentication completed successfully
I/wpa_supplicant( 1178): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE,
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WISPrService( 4224): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4224): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 1
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1,
D/WifiNative-wlan0(  906):    returned null,
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
,D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42530878): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424bc088 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424bc088 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0,
,W/fb4a(:<default>):StaticBindingVerifier( 4460): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4460): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4460): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3578
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3578:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  906): acquireWL(442003b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,D/PMS     (  906): acquireWL(42501108): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(442003b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  906): releaseWL(42501108): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1439): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/AutoSetting( 1392): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1392/10053)
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4489 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1392): Util - no network available!
,D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1392): service - mHandler: cancel location update
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1392/10053)
D/AutoSetting( 1392): service -           changes count: 0
,I/ActivityManager(  906): Recipient 3578
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4460): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4489): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4489): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4489): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4489): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4509 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4158
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4158:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4489/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4489/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4489/10078)
,I/ActivityManager(  906): Recipient 4158
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  906): Client connection lost with reason: 4
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4540 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3821
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  906): Killing 3821:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3821
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.961MB for 84664-byte allocation
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4460): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,W/GAV2    ( 4540): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4540): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): releaseWL(42530878): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.979MB for 28144-byte allocation
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4460): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/dalvikvm( 4460): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4460): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4460): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,W/dalvikvm( 4460): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4460): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4460): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1178): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
,D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=21506 delay=15s
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
,D/MDST    (  906): default: setTeardownRequested(true)
,D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WISPrService( 4224): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423af1d8
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.040MB for 39954-byte allocation
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43578280): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4489/10078)
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.116MB for 79892-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43aecdd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
D/PMS     (  906): releaseWL(43578280): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(43aa9278): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): releaseWL(43aecdd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
I/CheckinService( 1222): Preparing to send checkin request
,I/EventLogService( 1222): Accumulating logs since 1452271951082
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,V/WebViewChromiumFactoryProvider( 4540): Binding Chromium to main looper Looper (main, tid 1) {41a86200}
,I/LibraryLoader( 4540): Expected native library version number "",actual native library version number ""
,I/chromium( 4540): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4540): Initializing chromium process, renderers=0
,I/GoogleHttpClient( 1222): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1222): Using GMS GoogleHttpClient
,D/PMS     (  906): acquireWL(43b3fe40): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/PMS     (  906): acquireWL(43f43bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): releaseWL(43f43bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4540): BLUETOOTH permission is missing!
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
I/Adreno-EGL( 4540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4540): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4540): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4540): Local Branch: 
I/Adreno-EGL( 4540): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4540): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4540):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1439): GoogleAccountDataService.getToken()
,I/NSApplication( 4540): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1439): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.281MB for 75760-byte allocation
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
,D/Process (  906): killProcessQuiet, pid=3967
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3967:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 1222): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433b4320 u0 ReceiverList{4328fff0 4460 com.facebook.katana/10026/u0 remote:42be3b50}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433b4320 u0 ReceiverList{4328fff0 4460 com.facebook.katana/10026/u0 remote:42be3b50}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{439fd628 u0 ReceiverList{439fd5c8 4460 com.facebook.katana/10026/u0 remote:436933d0}}
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f5e750 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/GCM     ( 1439): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 16 6 12
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3967
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4595 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/wpa_supplicant( 1178): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1178): EAPOL: disable timer tick
D/PMS     (  906): acquireWL(43acb1f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1493 10028 null
,D/PMS     (  906): releaseWL(43acb1f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1493): Unknown pending intent to remove.
,I/MultiDex( 4595): install
,I/MultiDex( 4595): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  906): acquireWL(43505a70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1493 10028 null
D/PMS     (  906): releaseWL(43505a70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/MultiDex( 4595): loading existing secondary dex files
,I/MultiDex( 4595): load found 1 secondary dex files
,I/MultiDex( 4595): install done
,I/ProviderInstaller( 4595): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1439): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
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
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(43b96f20): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/NetworkMonitor( 3838): type=WIFI subType= reason=null isConnected=true
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(42b01f48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42b01f48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1493/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3838/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4278/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4489/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1868/1000)
I/acms    ( 1868): Checking Certificates
I/acms    ( 1868): Checking Developer Certificates
I/acms    ( 1868): Checking Application Certificates
I/acms    ( 1868): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1868): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1868): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1868): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1868): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1868): Updating next query delay: 75600000
I/mlserverapp( 1868): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1868): cancelACMSProgrammedChecks
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3873/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4278/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4349f1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2422/10021)
D/PMS     (  906): releaseWL(4349f1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42ae89d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42ae89d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1439): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/libc    ( 1439): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1439): [NET] getaddrinfo-,err=8
D/libc    ( 1439): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1439): [NET] getaddrinfo-, 1
,D/libc    ( 1439): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =201b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1392): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(436ba180): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1439 10028 null
,D/MobileConnectivityChangeReceiver( 4489): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4489): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1392): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1392): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1392): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1392): service - handleMessage() setting current location null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1392/10053)
,D/AutoSetting( 1392): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1392): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1392/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4540/10151)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 188
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1439): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1439): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1439): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  906): acquireWL(42c08c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
D/PMS     (  906): releaseWL(42c08c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4595): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/GCM     ( 1439): Connected
D/PMS     (  906): acquireWL(43452bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1439 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
,I/Adreno-EGL( 4595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4595): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4595): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4595): Local Branch: 
I/Adreno-EGL( 4595): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4595): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4595):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  906): releaseWL(436ba180): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1439/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  906): releaseWL(43452bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4402c5f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1439 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1439/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1439): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1439/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  906): releaseWL(4402c5f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43f5d870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
D/PMS     (  906): releaseWL(43f5d870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4595/10028)
,I/CheckinTask( 1222): Sending checkin request (9014 bytes)
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =63e0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 235
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,I/SensorManager(  906): mEventCount = 1350
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=14 [21][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4389): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4389): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4389): BLE is supported
I/jxcore-log( 4389): 
,D/PMS     (  906): acquireWL(43f09558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
,D/PMS     (  906): releaseWL(43f09558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
,W/GLSUser ( 1439): GoogleAccountDataService.getToken()
,W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1439): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ac04c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 8 3 12
,I/CheckinTask( 1222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1222): Unable to close GMS GoogleHttpClient
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/GCM     ( 1439): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(43aa9278): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b32860 that was originally bound here
E/ActivityThread( 1222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b32860 that was originally bound here
E/ActivityThread( 1222): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1222): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1222): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1222): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1222): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1222): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1222): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1222): 	at bks.a(SourceFile:298)
E/ActivityThread( 1222): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1222): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1439): GCM config loaded
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4460): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d6f5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  906): releaseWL(43b3fe40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42051d68
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42051d68, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421cce08
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@424d7f68
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,W/PMS     (  906): mWirelessDisplayManager is null
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 375ms
,D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,I/InputMethodManagerService(  906): Disable input method client, pid=4389
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42438e48),
W/ResourceType( 4389): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4389): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a8e3e8 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(43a92080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMS     (  906): acquireWL(43a2bca0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
I/WindowManager(  906): No lock screen! windowToken=null
I/BatteryService(  906): n_update end
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(43a2bca0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): releaseWL(43a92080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/MtpService( 2422): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting - 0
D/MtpService( 2422): [MTP][onReceive]-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1392): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  906): acquireWL(434c4e20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  906): releaseWL(434c4e20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1392): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=21507 delay=15s
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,I/ClockThread( 1117): stop update clock
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:On
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4224): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4224): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4224): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4224): Cust_ConnectToPC   : spcsc>false
D/        ( 4224): Cust_ConnectToPC   : IPT>true
,D/        ( 4224): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/Settings( 4224): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WIFI_ICON( 1117): WifiActivity: 0
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/SmartNS_Utility( 4224): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4224): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4224): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4224): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4224): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4224): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
W/Settings( 4224): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4224):  defaultType:0
D/WifiNative-wlan0(  906):    returned true
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4644 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(441e6320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1493 10028 null
,D/PMS     (  906): releaseWL(441e6320): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1807): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): onScreenOn: 1452272007482
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1807): onScreenOn: 1452272007482
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421cce08
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421cce08, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@424d7f68
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(424fcd68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(424fcd68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=21507 mDataStallAlarmIntent=PendingIntent{42e2c6e8: PendingIntentRecord{424b7c10 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(4323ac98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4644 1000 null
D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:Off
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43bc9bf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
D/PMS     (  906): releaseWL(4323ac98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4644): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/Process (  906): killProcessQuiet, pid=4244
D/PMS     (  906): releaseWL(43bc9bf8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  906): Killing 4244:com.google.android.partnersetup/u0a31 (adj 15): empty #17
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
D/SmartSyncUtils( 4644): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
I/ActivityManager(  906): Recipient 4244
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424d7f68
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424d7f68, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424d7f68, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424d7f68
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fa6c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fa6c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] getTotalRam: 1873 Mb
D/AutoSetting( 1392): service - mHandler: cancel location update
,D/AutoSetting( 1392): service -           changes count: 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1807): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1807): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1807): onScreenOff
D/PMS     (  906): acquireWL(42537020): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1493 10028 null
D/PMS     (  906): releaseWL(42537020): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/GAV2    ( 4540): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(4327c888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1493 10028 null
,D/PMS     (  906): acquireWL(435dfb80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1493 10028 null
,D/PMS     (  906): releaseWL(4327c888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(435dfb80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  906): killProcessQuiet, pid=4278
,I/ActivityManager(  906): Killing 4278:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4278
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4296
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4296:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4296
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.973MB for 29432-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.996MB for 44144-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 11.031MB for 66212-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 11.097MB for 78572-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 11.104MB for 79232-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 11.144MB for 69282-byte allocation
,D/libc    ( 4460): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4460): [NET] getaddrinfo-,err=8
D/libc    ( 4460): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4460): [NET] getaddrinfo-, 1
,D/libc    ( 4460): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cf73 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 44
D/libc    (  364): [NET]res_nsend:resplen=93
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4460): [NET] getaddrinfo_proxy-, success
,I/global  ( 4460): call createSocket() return a new socket.
D/libc    ( 4460): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4460): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4460): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4460): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43299fa0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4460 10026 null
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4460): I/O error closing connection
I/global  ( 4460): java.net.SocketException: Socket is closed
I/global  ( 4460): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4460): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4460): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4460): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4460): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4460): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4460): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4460): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4460): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4460): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4460): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4460): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4460): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4460): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4460): Removing a connection that never existed!
D/PMS     (  906): releaseWL(43299fa0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43fa2c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fa2c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1392): service - mHandler: update timezone
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1506): service - onCreate()
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1594): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1506): service - mHandler: update timezone
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1117): removeNotification.gc:56
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b0f990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  906): acquireWL(43bbb550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bbb550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(424102d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
,D/AutoSetting( 1392): service - handleMessage() stop self
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,V/AlarmManager(  906): sending alarm PendingIntent{422b5790: PendingIntentRecord{4244ecf0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143112, Int=0
D/PMS     (  906): acquireWL(431f9e68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{43a8e0c0: PendingIntentRecord{42540318 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143203, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
,D/PMS     (  906): releaseWL(424102d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c509 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(43a3c2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
D/PMS     (  906): releaseWL(43a3c2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1392): service - handleMessage() quit looper
,D/AutoSetting( 1392): service - onDestroy() END
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(43f26748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f26748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(431f9e68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=3873
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3873:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3873
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43b9b348 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4263
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4263:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4263
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4243e930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4243e930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43241e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43241e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43af3968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{425b82f8: PendingIntentRecord{43be2350 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228952, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4685 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4246c550: PendingIntentRecord{4254a8f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452272117223, Int=10800000
,D/PMS     (  906): releaseWL(43af3968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4685/10047)
,D/Process (  906): killProcessQuiet, pid=4319
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4319:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4319
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  906): acquireWL(424e9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43ba5a00: PendingIntentRecord{43be2350 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233074, Int=0
,D/PMS     (  906): releaseWL(424e9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(434a1378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434a1378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43a09498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a09498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43fc3aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fc3aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43435688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=325560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43435688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4389): Connected to the server!
I/jxcore-log( 4389): 
,I/chromium( 4389): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4389): --- start :testFindPeers.js---
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): testFindPeers created [object Object]
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): serverPort is 8876
I/jxcore-log( 4389): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4389): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4389): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4389): start: Peer ID: 80:01:84:8A:B3:68, peer name: HTC Desire 820
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4389): bind: Binding a new listener
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4389): initialize: My bluetooth address is 80:01:84:8A:B3:68
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4389): verifyIdentityString: Identity string created: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC Desire 820"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4389): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 4389): getBluetoothService(): entry
,W/BluetoothAdapter( 4389): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1622): SOCK FLAG = 0 ***********************
I/bt-btif ( 1622): BTA_JvCreateRecordByUser
D/bt-btm  ( 1622): BTM_AllocateSCN
D/bt-sdp  ( 1622): SDP_CreateRecord ok, num_records:17
I/bt-btif ( 1622): BTA_JvRfcommStartServer
,I/bt-btm  ( 1622): BTM_SEC_REG[19]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 1622):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4389): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4389): start: OK
,I/io.jxcore.node.ConnectionHelper( 4389): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4389): start: Peer ID: 80:01:84:8A:B3:68, peer name: HTC Desire 820
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4389): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4389): bind: Binding a new listener
,W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4389): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
,W/dalvikvm( 4389): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;),
W/dalvikvm( 4389): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
E/dalvikvm( 4389): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4389): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4389): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4389): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/dalvikvm( 4389): threadid=1: thread exiting with uncaught exception (group=0x4164fe30),
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at android.os.Looper.loop(Looper.java:157)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): 	at dalvik.system.NativeStart.main(Native Method)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43fdc7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fdc7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/GLSUser ( 1439): GoogleAccountDataService.getToken()
,W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1439): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1439): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1439): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1439): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1439): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1439): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1439): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1439): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,E/PlayEventLogger( 4187): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4187): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4187): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4187): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4187): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4187): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4187): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4187): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cbaaa0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 9 3 12
,D/libc    ( 4187): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4187): [NET] getaddrinfo-,err=8
D/libc    ( 4187): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4187): [NET] getaddrinfo-, 1
,D/libc    ( 4187): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5f6f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 258
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo_proxy-, success
I/global  ( 4187): call createSocket() return a new socket.
D/libc    ( 4187): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4187): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4187): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4187): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(4369a5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4369a5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(424e46e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{424ae060: PendingIntentRecord{4402e348 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=412732, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{438001a0: PendingIntentRecord{437fea30 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1452272254323, Int=0
,D/PMS     (  906): releaseWL(424e46e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1222): No account for auth token provided
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9b82 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
I/global  ( 1222): call createSocket() return a new socket.
D/libc    ( 1222): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(436b9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436b9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43a99f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=445560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a99f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/bt-btm  ( 1622): btm_dev_support_switch return FALSE
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
I/bt-btm  ( 1622): btm_sec_alloc_dev
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [7cf90e3796ab]
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/bt-btm  ( 1622): BTM_GetHCIConnHandle
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(42db2b90): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_acl_resubmit_page
,D/bt-btm  ( 1622): btm_acl_created hci_handle=1 link_role=1  is_le_link=0
D/bt-btm  ( 1622): device_type=0x0
D/bt-btm  ( 1622): btm_read_remote_features() handle: 1
D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): is_originator:0 
I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x0 Flags:0x80 State:0
I/bt-btm  ( 1622): Security Manager: Start get name
D/bt-btm  ( 1622): btm_acl_paging discing:0, paging:0 BDA: 7cf90e3796ab
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_acl_update_busy_level
D/bt-btm  ( 1622): BTM_BLI_PAGE_DONE_EVT
D/bt-btm  ( 1622): btm_acl_created hci_handle=1 link_role=1  is_le_link=0
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): Duplicate btm_acl_created: RemBdAddr: 7cf90e3796ab
,D/bt-btm  ( 1622): BTM_SetLinkPolicy
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_SetLinkSuperTout
,D/bt-btm  ( 1622): btm_process_clk_off_comp_evt
D/bt-btm  ( 1622): btm_handle_to_acl_index
,I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [7cf90e3796ab]
,D/bt-btm  ( 1622): btm_proc_lsto_evt,
,D/bt-btm  ( 1622): btm_read_remote_version_complete
,D/bt-btm  ( 1622): btm_read_remote_features_complete
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): Start reading remote extended features
,D/bt-btm  ( 1622): btm_read_remote_ext_features() handle: 1 page: 1
I/bt-btm  ( 1622): BDA 7c:f9:0e:37:96:ab
,I/bt-btm  ( 1622): Inquire BDA 00:00:00:00:00:00
I/bt-btm  ( 1622): btm_sec_rmt_name_request_complete
D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): setting BTM_SEC_NAME_KNOWN sec_flags:0x88
I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x0 Flags:0x88 State:0
I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1622): Security Manager: access granted
,D/bt-btm  ( 1622): btm_read_remote_ext_features_complete
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): BTM reads next remote extended features page (2)
,D/bt-btm  ( 1622): btm_read_remote_ext_features() handle: 1 page: 2
,D/bt-btm  ( 1622): btm_read_remote_ext_features_complete
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): BTM reached last remote extended features page (2)
D/bt-btm  ( 1622): btm_process_remote_ext_features
I/bt-btm  ( 1622): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
,D/bt-btm  ( 1622): btm_establish_continue
D/bt-btm  ( 1622): btm_set_packet_types
D/bt-btm  ( 1622): SetPacketType Mask -> 0xcc18
D/bt-btm  ( 1622): BTM_SetLinkPolicy
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
D/bt-btm  ( 1622): btm_acl_update_busy_level
,D/bt-btm  ( 1622): BTM_BLI_ACL_UP_EVT
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,W/bt-btif ( 1622): info:x10
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,I/bt-btif ( 1622): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 1622): aclStateChangeCallback: Device is NULL
,D/bt-att  ( 1622): GATT   ATT protocol channel with BDA: 7cf90e3796ab is connected
D/bt-att  ( 1622): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-btm  ( 1622): btm_sec_is_a_bonded_dev is_bonded=0
D/bt-att  ( 1622): connected is TRUE reason=0
,I/bt-smp  ( 1622): SMDBG l2c smp_connect_cback 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b7c38
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x40
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x40
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 0
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 8 pairing_flags:0x0
D/bt-btm  ( 1622): btm_io_capabilities_rsp : rmt_io_caps is 0 
I/bt-btm  ( 1622): btm_io_capabilities_req() State: 8
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-btm  ( 1622): btm_io_capabilities_req() State: 8  Flags: 0x0000  p_cur_service: 0x00000000
I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 8
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 7 pairing_flags:0x0
,I/bt-btm  ( 1622): btm_io_capabilities_req: State: 7  IO_CAP:1 oob_data:0 auth_req:0
,I/bt-btm  ( 1622): btm_proc_sp_req_evt() BDA: 7cf90e3796ab event: 0x2, State: 7
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 7
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 4 pairing_flags:0x0
D/bt-btm  ( 1622): btm_proc_sp_req_evt()  just_works:1, io loc:1, rmt:1, auth loc:0, rmt:0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothRemoteDevices( 1622): Remote class is:5898764
,I/bt-btif ( 1622): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 1622): check_cod: remote_cod = 0x5a020c
I/bt-btm  ( 1622): BTM_ConfirmReqReply() State: 4  Res: 0
I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 4
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 9 pairing_flags:0x0
I/BluetoothBondStateMachine( 1622): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1622): Entering PendingCommandState State
,V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1622): action: android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothAdapter( 1807): getBluetoothService(): entry
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothAdapter( 1807): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 1807): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41afe0b0
D/BluetoothDevice( 1807): getService : Register callback
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1807): isLeDevice: 7C:F9:0E:37:96:AB
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423ce858:true
,V/BluetoothSapService( 1622): state: -2147483648
D/BluetoothAdapter( 4224): getBluetoothService(): entry
D/BluetoothAdapter( 4224): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 4224): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41be51a8
,D/BluetoothDevice( 4224): getService : Register callback
,I/bt-btm  ( 1622): btm_simple_pair_complete()  Pair State: 9  Status:0  sec_state: 0
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-btm  ( 1622): btm_sec_link_key_notification()  BDA:7cf90e3796ab, TYPE: 4
I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 9
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 0 pairing_flags:0x0
,I/bt-btm  ( 1622): BTM_IsInquiryActive
I/bt-btm  ( 1622): BTM_IsRNRActive
,I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [7cf90e3796ab]
I/bt-btm  ( 1622): BTM_ReadRemoteDeviceName: bd addr [7cf90e3796ab]
,I/bt-btm  ( 1622): no device found in inquiry db
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_acl_paging discing:0, paging:0 BDA: 7cf90e3796ab
,D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btm  ( 1622): BDA 7c:f9:0e:37:96:ab
I/bt-btm  ( 1622): Inquire BDA 7c:f9:0e:37:96:ab
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btm  ( 1622): btm_sec_rmt_name_request_complete
D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btm  ( 1622): setting BTM_SEC_NAME_KNOWN sec_flags:0xba
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [7cf90e3796ab]
,I/bt-btm  ( 1622): BTM_IsAclConnectionUp: RemBdAddr: 7cf90e3796ab
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_bda_to_acl found
,E/bt-btif ( 1622): services_to_search = 3fffffff
,E/bt-btif ( 1622): ****************search UUID = 1200***********
I/bt-sdp  ( 1622): SDP - Originate started
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:1, 0x620b7d94
,I/bt-btm  ( 1622): btm_find_or_alloc_dev,
,D/bt-btm  ( 1622): btm_acl_encrypt_change handle=1 status=0 encr_enabl=1
D/bt-btm  ( 1622): btm_handle_to_acl_index
I/bt-btm  ( 1622): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xba
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xbe
,D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b7ef0
I/bt-btm  ( 1622): btm_find_or_alloc_dev
D/bt-btm  ( 1622): btm_sec_l2cap_access_req()  sm4:0x11, sec_flags:0xbe, security_required:0x86 chk:1
D/bt-btm  ( 1622): no next_serv sm4:0x11, chk:1
D/bt-btm  ( 1622): (SM4 to SM4) btm_sec_l2cap_access_req rspd. authenticated: x2, enc: x4
D/bt-btm  ( 1622): btm_sec_check_upgrade...
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1622): Security Manager: l2cap_access_req PSM:3 Handle:1 State:0 Flags:0xbe Required:0x86 Service ID:42
I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x86 Flags:0xbe State:0
I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1622): Security Manager: access granted
,I/bt-sdp  ( 1622): SDP - got conn cnf, sent cfg req, CID: 0x41
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x41
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x41  Result: 0
,W/bt-sdp  ( 1622): process_service_search_attr_rsp
,I/bt-sdp  ( 1622): SDP - disconnect  CID: 0x41
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc cfm, CID: 0x41
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,E/bt-btif ( 1622): services_to_search = 3ffffffe
E/bt-btif ( 1622): ****************search UUID = 0100***********
I/bt-sdp  ( 1622): SDP - Originate started
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:1, 0x620b804c
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,D/bt-btm  ( 1622): btm_sec_mx_access_request is_originator:0
I/bt-btm  ( 1622): btm_find_or_alloc_dev
D/bt-btm  ( 1622): btm_sec_find_mx_serv
,D/bt-btm  ( 1622): btm_sec_check_upgrade...
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
,D/bt-btm  ( 1622): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1622): Security Manager: mx_access_req proto_id:3 chan_id:4 State:0 Flags:0xbe Required:0x80 Service ID:58
,I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x80 Flags:0xbe State:0
I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1622): Security Manager: access granted
,I/bt-btif ( 1622): BTA_JVSetPmProfile handle:0x87, app_id:255
,I/bt-sdp  ( 1622): SDP - got conn cnf, sent cfg req, CID: 0x43
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x43
I/bt-btif ( 1622): bta_jv_set_pm_profile(handle: 0x87, app_id: 255, init_st: 0)
I/bt-btif ( 1622): bta_jv_alloc_set_pm_profile_cb(handle 0x87, app_id 255): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x620bda4c
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 0)
D/BluetoothAdapter( 4389): getBluetoothService(): entry
W/bt-btif ( 1622): new conn_srvc id:26, app_id:255
W/bt-btif ( 1622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1622): bta_dm_pm_ssr:2, lat:1200
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/BluetoothAdapter( 4389): getBluetoothService(): callingUser = 0 callingUid = 10348 callingAppId = 10348
D/BluetoothAdapter( 4389): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@425e64d0
D/BluetoothDevice( 4389): getService : Register callback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Incoming connection initialized (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4389): Entering thread (ID: 473),
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x43  Result: 0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): onBytesRead: Read 63 bytes successfully (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): onBytesWritten: 73 bytes successfully written (thread ID: 473)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): removeThreadFromList: Removing thread with ID 473
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Handshake thread disposed (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4389): Exiting thread (ID: 473)
D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btif ( 1622): BTA_JvRfcommWrite,
I/bt-btif ( 1622): write ok
,D/bt-btm  ( 1622): write ok,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,W/bt-sdp  ( 1622): process_service_search_attr_rsp
,I/bt-sdp  ( 1622): SDP - disconnect  CID: 0x43
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc cfm, CID: 0x43
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,E/bt-btif ( 1622): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/bt-btif ( 1622): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
I/bt-btif ( 1622): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothAdapterProperties( 1622): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 1622): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1807): isLeDevice: 7C:F9:0E:37:96:AB
V/BluetoothSapService( 1622): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1622): state: -2147483648
,I/BluetoothBondStateMachine( 1622): StableState(): Entering Off State
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found,
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found,
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
E/bt-btif ( 1622): send none, EAGAIN or EWOULDBLOCK, errno:11
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found,
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,D/PMS     (  906): acquireWL(43f8d5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f8d5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x2
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock released
D/PMS     (  906): releaseWL(42db2b90): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PMS     (  906): acquireWL(431c3190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(431c3190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
,D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,I/bt-btm  ( 1622): btm_sec_alloc_dev
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [b0c5593f7569]
D/bt-btm  ( 1622): BTM_GetHCIConnHandle
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(42c58128): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_acl_role_changed
,D/bt-btm  ( 1622): btm_acl_resubmit_page
,D/bt-btm  ( 1622): btm_acl_created hci_handle=2 link_role=1  is_le_link=0
D/bt-btm  ( 1622): device_type=0x0
D/bt-btm  ( 1622): btm_read_remote_features() handle: 2
D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): is_originator:0 
,I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x0 Flags:0x80 State:0
I/bt-btm  ( 1622): Security Manager: Start get name
D/bt-btm  ( 1622): btm_acl_paging discing:0, paging:0 BDA: b0c5593f7569
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_acl_update_busy_level
D/bt-btm  ( 1622): BTM_BLI_PAGE_DONE_EVT
D/bt-btm  ( 1622): btm_acl_created hci_handle=2 link_role=0  is_le_link=0
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): Duplicate btm_acl_created: RemBdAddr: b0c5593f7569
D/bt-btm  ( 1622): BTM_SetLinkPolicy,
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_SetLinkSuperTout
,D/bt-btm  ( 1622): btm_process_clk_off_comp_evt
,D/bt-btm  ( 1622): btm_handle_to_acl_index
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [b0c5593f7569]
,D/bt-btm  ( 1622): btm_read_remote_version_complete
D/bt-btm  ( 1622): btm_read_remote_features_complete
D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): Start reading remote extended features
,D/bt-btm  ( 1622): btm_read_remote_ext_features() handle: 2 page: 1
,I/bt-btm  ( 1622): BDA b0:c5:59:3f:75:69
,I/bt-btm  ( 1622): Inquire BDA 00:00:00:00:00:00
I/bt-btm  ( 1622): btm_sec_rmt_name_request_complete
D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btm  ( 1622): setting BTM_SEC_NAME_KNOWN sec_flags:0x88
I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x0 Flags:0x88 State:0
,I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1622): Security Manager: access granted
,D/bt-btm  ( 1622): btm_read_remote_ext_features_complete
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): BTM reads next remote extended features page (2)
,D/bt-btm  ( 1622): btm_read_remote_ext_features() handle: 2 page: 2
,D/bt-btm  ( 1622): btm_read_remote_ext_features_complete
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): BTM reached last remote extended features page (2)
,D/bt-btm  ( 1622): btm_process_remote_ext_features
I/bt-btm  ( 1622): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
,D/bt-btm  ( 1622): btm_establish_continue
D/bt-btm  ( 1622): btm_set_packet_types
,D/bt-btm  ( 1622): SetPacketType Mask -> 0xcc18
,D/bt-btm  ( 1622): BTM_SetLinkPolicy
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,D/bt-btm  ( 1622): btm_acl_update_busy_level
D/bt-btm  ( 1622): BTM_BLI_ACL_UP_EVT
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
W/bt-btif ( 1622): info:x10,
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,I/bt-btm  ( 1622): BTM_SwitchRole BDA: 7c-f9-0e-37-96-ab
D/bt-btm  ( 1622): btm_bda_to_acl found,
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
I/bt-btm  ( 1622): BTM_SwitchRole BDA: b0-c5-59-3f-75-69
D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btif ( 1622): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 1622): aclStateChangeCallback: Device is NULL,
,D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): btm_acl_role_changed
,D/bt-btm  ( 1622): btm_acl_report_role_change
,D/bt-btm  ( 1622): Role Switch Event: new_role 0x01, HCI Status 0x00, rs_st:0
E/bt-btm  ( 1622): tBTM_SEC_DEV:0x6209e3f4 rs_disc_pending=0,
W/bt-btif ( 1622): bta_dm_check_av:0
,W/bt-btif ( 1622): btif_dm_cback : unhandled event (14)
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,D/bt-btm  ( 1622): btm_proc_lsto_evt
,I/bt-btm  ( 1622): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_acl_role_changed
,D/bt-btm  ( 1622): btm_acl_report_role_change
D/bt-btm  ( 1622): Role Switch Event: new_role 0x01, HCI Status 0x21, rs_st:0
,E/bt-btm  ( 1622): tBTM_SEC_DEV:0x6209e238 rs_disc_pending=1
,W/bt-btif ( 1622): bta_dm_check_av:0
D/bt-btm  ( 1622): BTM_GetRole
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_SetLinkPolicy,
I/bt-btm  ( 1622): BTM_SetLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,W/bt-btif ( 1622): btif_dm_cback : unhandled event (14)
,D/bt-att  ( 1622): GATT   ATT protocol channel with BDA: b0c5593f7569 is connected
,D/bt-att  ( 1622): gatt_is_bda_in_the_srv_chg_clt_list :b0-c5-59-3f-75-69
D/bt-btm  ( 1622): btm_sec_is_a_bonded_dev is_bonded=0
D/bt-att  ( 1622): connected is TRUE reason=0
,I/bt-smp  ( 1622): SMDBG l2c smp_connect_cback 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b81a8
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x44
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x44
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x44  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x44
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 0
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 8 pairing_flags:0x0
,D/bt-btm  ( 1622): btm_io_capabilities_rsp : rmt_io_caps is 0 
,I/bt-btm  ( 1622): btm_io_capabilities_req() State: 8
I/bt-btm  ( 1622): btm_find_or_alloc_dev
I/bt-btm  ( 1622): btm_io_capabilities_req() State: 8  Flags: 0x0000  p_cur_service: 0x00000000
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 8
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 7 pairing_flags:0x0
,I/bt-btm  ( 1622): btm_io_capabilities_req: State: 7  IO_CAP:1 oob_data:0 auth_req:0
,D/PMS     (  906): acquireWL(435a4bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=505560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/bt-btm  ( 1622): btm_proc_sp_req_evt() BDA: b0c5593f7569 event: 0x2, State: 7
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 7
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 4 pairing_flags:0x0
D/bt-btm  ( 1622): btm_proc_sp_req_evt()  just_works:1, io loc:1, rmt:1, auth loc:0, rmt:0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothRemoteDevices( 1622): Remote class is:5898764
,I/bt-btif ( 1622): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 1622): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 1622): check_cod: remote_cod = 0x5a020c
I/bt-btm  ( 1622): BTM_ConfirmReqReply() State: 4  Res: 0
I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 4
,I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 9 pairing_flags:0x0
,D/PMS     (  906): releaseWL(435a4bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/BluetoothBondStateMachine( 1622): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1622): Entering PendingCommandState State
V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.BOND_STATE_CHANGED
V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1807): isLeDevice: B0:C5:59:3F:75:69
V/BluetoothSapService( 1622): action: android.bluetooth.device.action.BOND_STATE_CHANGED
V/BluetoothSapService( 1622): state: -2147483648
,I/bt-btm  ( 1622): btm_simple_pair_complete()  Pair State: 9  Status:0  sec_state: 0
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-btm  ( 1622): btm_sec_link_key_notification()  BDA:b0c5593f7569, TYPE: 4
I/bt-btm  ( 1622): btm_sec_change_pairing_state  Old: 9
I/bt-btm  ( 1622): btm_sec_change_pairing_state  New: 0 pairing_flags:0x0
I/bt-btm  ( 1622): BTM_IsInquiryActive
,I/bt-btm  ( 1622): BTM_IsRNRActive
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [b0c5593f7569]
I/bt-btm  ( 1622): BTM_ReadRemoteDeviceName: bd addr [b0c5593f7569]
,I/bt-btm  ( 1622): no device found in inquiry db
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_acl_paging discing:0, paging:0 BDA: b0c5593f7569
,D/bt-btm  ( 1622): btm_bda_to_acl found
,I/bt-btm  ( 1622): BDA b0:c5:59:3f:75:69
,I/bt-btm  ( 1622): Inquire BDA b0:c5:59:3f:75:69
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): btm_sec_rmt_name_request_complete
,D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): setting BTM_SEC_NAME_KNOWN sec_flags:0xba
D/bt-btm  ( 1622): btm_acl_encrypt_change handle=2 status=0 encr_enabl=1
,D/bt-btm  ( 1622): btm_handle_to_acl_index
I/bt-btm  ( 1622): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xba
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xbe,
D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): BTM_InqDbRead: bd addr [b0c5593f7569]
I/bt-btm  ( 1622): BTM_IsAclConnectionUp: RemBdAddr: b0c5593f7569,
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
,E/bt-btif ( 1622): services_to_search = 3fffffff
E/bt-btif ( 1622): ****************search UUID = 1200***********,
I/bt-sdp  ( 1622): SDP - Originate started
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:1, 0x620b8304
I/bt-btm  ( 1622): btm_find_or_alloc_dev
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8460
I/bt-btm  ( 1622): btm_find_or_alloc_dev
D/bt-btm  ( 1622): btm_sec_l2cap_access_req()  sm4:0x11, sec_flags:0xbe, security_required:0x86 chk:1
D/bt-btm  ( 1622): no next_serv sm4:0x11, chk:1
D/bt-btm  ( 1622): (SM4 to SM4) btm_sec_l2cap_access_req rspd. authenticated: x2, enc: x4
D/bt-btm  ( 1622): btm_sec_check_upgrade...
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
,I/bt-btm  ( 1622): Security Manager: l2cap_access_req PSM:3 Handle:2 State:0 Flags:0xbe Required:0x86 Service ID:42
I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x86 Flags:0xbe State:0
I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1622): Security Manager: access granted
,I/bt-sdp  ( 1622): SDP - got conn cnf, sent cfg req, CID: 0x45
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x45
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x45  Result: 0
,W/bt-sdp  ( 1622): process_service_search_attr_rsp
I/bt-sdp  ( 1622): SDP - disconnect  CID: 0x45
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc cfm, CID: 0x45
D/bt-sdp  ( 1622): releasing SDP rsp_list
,E/bt-btif ( 1622): services_to_search = 3ffffffe
E/bt-btif ( 1622): ****************search UUID = 0100***********
I/bt-sdp  ( 1622): SDP - Originate started
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:1, 0x620b85bc
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
D/bt-btm  ( 1622): btm_sec_mx_access_request is_originator:0
I/bt-btm  ( 1622): btm_find_or_alloc_dev
D/bt-btm  ( 1622): btm_sec_find_mx_serv
D/bt-btm  ( 1622): btm_sec_check_upgrade...
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1622): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1622): Security Manager: mx_access_req proto_id:3 chan_id:4 State:0 Flags:0xbe Required:0x80 Service ID:58
,I/bt-btm  ( 1622): btm_sec_execute_procedure: Required:0x80 Flags:0xbe State:0
I/bt-btm  ( 1622): Security Manager: trusted:0x00000000
I/bt-btm  ( 1622): Security Manager: access granted
I/bt-btif ( 1622): BTA_JVSetPmProfile handle:0x187, app_id:255
I/bt-btif ( 1622): bta_jv_set_pm_profile(handle: 0x187, app_id: 255, init_st: 0)
,I/bt-btif ( 1622): bta_jv_alloc_set_pm_profile_cb(handle 0x187, app_id 255): idx: 1, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x620bda60
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 0)
I/bt-btm  ( 1622): BTM_SwitchRole BDA: 7c-f9-0e-37-96-ab
D/bt-btm  ( 1622): btm_bda_to_acl found
I/bt-btm  ( 1622): BTM_SwitchRole BDA: b0-c5-59-3f-75-69
D/bt-btm  ( 1622): btm_bda_to_acl found
W/bt-btif ( 1622): new conn_srvc id:26, app_id:255
W/bt-btif ( 1622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1622): bta_dm_pm_ssr:2, lat:1200
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Incoming connection initialized (thread ID: 474)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4389): Entering thread (ID: 474)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Waiting for incoming connections...,
,I/bt-sdp  ( 1622): SDP - got conn cnf, sent cfg req, CID: 0x47,
,D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): btm_get_max_packet_size,
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x47
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x47  Result: 0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): onBytesRead: Read 81 bytes successfully (thread ID: 474)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): onBytesWritten: 73 bytes successfully written (thread ID: 474)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): removeThreadFromList: Removing thread with ID 474
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4389): Handshake thread disposed (thread ID: 474)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4389): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4389): Exiting thread (ID: 474)
I/bt-btif ( 1622): BTA_JvRfcommWrite
I/bt-btif ( 1622): write ok
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_acl_role_changed
D/bt-btm  ( 1622): btm_acl_report_role_change
D/bt-btm  ( 1622): Role Switch Event: new_role 0x01, HCI Status 0x21, rs_st:0
,E/bt-btm  ( 1622): tBTM_SEC_DEV:0x6209e238 rs_disc_pending=1
W/bt-btif ( 1622): bta_dm_check_av:0
D/bt-btm  ( 1622): BTM_GetRole
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_SetLinkPolicy
D/bt-btm  ( 1622): btm_bda_to_acl found
,W/bt-btif ( 1622): btif_dm_cback : unhandled event (14)
,I/bt-btm  ( 1622): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_acl_role_changed
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_SetLinkSuperTout
,D/bt-btm  ( 1622): btm_acl_report_role_change
D/bt-btm  ( 1622): Role Switch Event: new_role 0x00, HCI Status 0x00, rs_st:0
E/bt-btm  ( 1622): tBTM_SEC_DEV:0x6209e3f4 rs_disc_pending=1
,W/bt-btif ( 1622): bta_dm_check_av:0
,W/bt-btif ( 1622): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 1622): process_service_search_attr_rsp
,I/bt-sdp  ( 1622): SDP - disconnect  CID: 0x47
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc cfm, CID: 0x47
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,E/bt-btif ( 1622): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1622): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1622): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/bt-btif ( 1622): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 1622): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothAdapterProperties( 1622): Failed to remove device: B0:C5:59:3F:75:69
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1807): isLeDevice: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 1622): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1622): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1622): state: -2147483648
,I/BluetoothBondStateMachine( 1622): StableState(): Entering Off State
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures,
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7),
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found,
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found,
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0,
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0,
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
E/bt-btif ( 1622): send none, EAGAIN or EWOULDBLOCK, errno:11
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6),
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1622): bta_jv_pm_state_change(p_cb: 0x620bdc0c, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
,W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
,W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 1
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 15, lmp_sub_version= 24844
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x2
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  906): releaseWL(42c58128): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1622): Wake lock released
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8718
I/bt-btm  ( 1622): btm_find_or_alloc_dev
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x48
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(434a77a8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x48
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x48  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x48
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled,
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0,
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock released
D/PMS     (  906): releaseWL(434a77a8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8874
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x49
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x49
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x49  Result: 0
D/PMS     (  906): acquireWL(43ef0800): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x49
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b89d0
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4a
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4a
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x4a  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x4a
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock released
D/PMS     (  906): releaseWL(43ef0800): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8b2c
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4b
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(4251f9c8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4b
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x4b  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x4b
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8c88
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4c,
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4c,
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x4c  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x4c
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
,W/bt-btif ( 1622): lmp_version = 7, manufacturer = 15, lmp_sub_version= 24844
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 1
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock released
D/PMS     (  906): releaseWL(4251f9c8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(43409e30): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8de4
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x4d
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x4d
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x4d  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x4d
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b7c38
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x40
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x40
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b7d94
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x41
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x41
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x41  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x41
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b804c
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x43
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x43
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x43  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 0e3796ab mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x43
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,D/PMS     (  906): acquireWL(436c5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436c5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
W/bt-btif ( 1622): lmp_version = 7, manufacturer = 15, lmp_sub_version= 24844
,W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x12
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 1
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
,D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteVersion
W/bt-btif ( 1622): lmp_version = 7, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 0e3796ab mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
D/bt-btm  ( 1622): btm_handle_to_acl_index
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  906): releaseWL(43409e30): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1622): Wake lock released
,D/bt-btm  ( 1622): btm_handle_to_acl_index
D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b81a8
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x44,
D/PMS     (  906): acquireWL(425aa9e8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x44
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x44  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x44
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,D/PMS     (  906): acquireWL(43674b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=565560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43674b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
W/bt-btif ( 1622): lmp_version = 7, manufacturer = 15, lmp_sub_version= 24844
W/bt-btif ( 1622): enable sniff,
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x12
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock released
D/PMS     (  906): releaseWL(425aa9e8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,D/bt-btm  ( 1622): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b8304
,I/bt-btm  ( 1622): btm_find_or_alloc_dev
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x45
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
D/PMS     (  906): acquireWL(43f3dd00): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x45
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x45  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x45
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1622): btm_sec_l2cap_access_req is_originator:0, 0x620b85bc
I/bt-btm  ( 1622): btm_find_or_alloc_dev
,I/bt-sdp  ( 1622): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x47
,D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): btm_get_max_packet_size
,I/bt-sdp  ( 1622): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x47
,I/bt-sdp  ( 1622): SDP - Rcvd cfg cfm, CID: 0x47  Result: 0
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 128 BDA: 593f7569 mode:0x0
,D/bt-btm  ( 1622): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1622): SDP - Rcvd L2CAP disc, CID: 0x47
,D/bt-sdp  ( 1622): releasing SDP rsp_list
,W/bt-btif ( 1622): dm_pm_timer expires
,W/bt-btif ( 1622): dm_pm_timer expires 0
W/bt-btif ( 1622): proc dm_pm_timer expires
W/bt-btif ( 1622): BTA_DM_PM_SNIFF
W/bt-btif ( 1622): check RemoteVersion
D/bt-btm  ( 1622): btm_bda_to_acl found
,D/bt-btm  ( 1622): BTM_ReadRemoteVersion
W/bt-btif ( 1622): lmp_version = 7, manufacturer = 15, lmp_sub_version= 24844
W/bt-btif ( 1622): enable sniff
,I/bt-btm  ( 1622): BTM_SetPowerMode: pm_id 0 BDA: 593f7569 mode:0x12,
,D/bt-btm  ( 1622): btm_handle_to_acl_index,
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1622): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1622): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled,
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0,
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  906): releaseWL(43f3dd00): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1622): Wake lock released
,D/bt-btm  ( 1622): btm_handle_to_acl_index
,I/bt-btif ( 1622): BTA_JvRfcommClose
,D/bt-att  ( 1622): GATT   ATT protocol channel with BDA: 7cf90e3796ab is disconnected
W/bt-btif ( 1622): invalid rfc slot id: 7
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
D/bt-att  ( 1622): gatt_is_bda_in_the_srv_chg_clt_list :7c-f9-0e-37-96-ab
D/bt-btm  ( 1622): btm_sec_is_a_bonded_dev is_bonded=1
D/bt-att  ( 1622): gatt_add_srv_chg_clt
D/bt-att  ( 1622): enqueue a srv chg client
D/bt-att  ( 1622): gatt_cleanup_upon_disc 
D/bt-att  ( 1622): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1622): ATT disconnected
I/bt-smp  ( 1622): SMDBG l2c smp_connect_cback 
D/bt-btm  ( 1622): btm_acl_removed
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_acl_report_role_change
D/bt-btm  ( 1622): btm_acl_update_busy_level
D/bt-btm  ( 1622): BTM_BLI_ACL_DOWN_EVT
D/bt-btm  ( 1622): acl hci_handle=1 is_le_link=0 connectable_mode=0x0 link_role=1
D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): Bletooth link down
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xb8
D/bt-btm  ( 1622): btm_acl_resubmit_page
E/bt-btm  ( 1622): btm_sec_disconnected - Clearing Pending flag
I/bt-btm  ( 1622): before Update sec_flags=0xb8
D/bt-btm  ( 1622): btm_ble_update_mode_operation adv_mode = 0
I/bt-btm  ( 1622): after Update sec_flags=0xb8
I/bt-btif ( 1622): bta_jv_free_set_pm_profile_cb(jv_handle: 0x87), idx: 0, app_id: 0xff
I/bt-btm  ( 1622): BTM_SwitchRole BDA: 7c-f9-0e-37-96-ab
I/bt-btm  ( 1622): BTM_SwitchRole BDA: b0-c5-59-3f-75-69
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
,D/bt-btm  ( 1622): btm_get_acl_disc_reason_code
D/BluetoothRemoteDevices( 1622): Wake lock Aquired
,I/bt-btif ( 1622): HAL bt_hal_cbacks->acl_state_changed_cb
,D/PMS     (  906): acquireWL(43685d00): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
D/BluetoothAdapterService(1101640176)( 1622): Get ACL Connected Devices being called
E/BluetoothAdapterProperties( 1622): setAclConnectedDevices failed to remove device: 7C:F9:0E:37:96:AB
D/BluetoothRemoteDevices( 1622): aclStateChangeCallback: State:DisConnected to Device:7C:F9:0E:37:96:AB
,V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.ACL_DISCONNECTED
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42313910:true
D/BluetoothAdapter( 2867): getBluetoothService(): entry
D/BluetoothAdapter( 2867): getBluetoothService(): callingUser = 0 callingUid = 10085 callingAppId = 10085
D/BluetoothAdapter( 2867): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41d634e8
D/BluetoothDevice( 2867): getService : Register callback
,V/BluetoothSapService( 1622): action: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1622): state: -2147483648
,E/BluetoothDevice( 2867): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2867): getBluetoothClass(): COD is 5898764
,I/BTConnectionReceiver( 2867): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2867): Bluetooth Device Name: A5-1
,D/BluetoothAdapter( 1838): getBluetoothService(): entry
,D/BluetoothAdapter( 1838): getBluetoothService(): callingUser = 0 callingUid = 10178 callingAppId = 10178
D/BluetoothAdapter( 1838): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@420ae138
,D/BluetoothDevice( 1838): getService : Register callback
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  906): releaseWL(43685d00): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1622): Wake lock released
,I/bt-btif ( 1622): BTA_JvRfcommClose
,D/bt-att  ( 1622): GATT   ATT protocol channel with BDA: b0c5593f7569 is disconnected
E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
D/bt-att  ( 1622): gatt_is_bda_in_the_srv_chg_clt_list :b0-c5-59-3f-75-69
D/bt-btm  ( 1622): btm_sec_is_a_bonded_dev is_bonded=1
D/bt-att  ( 1622): gatt_add_srv_chg_clt
D/bt-att  ( 1622): enqueue a srv chg client
,D/BluetoothRemoteDevices( 1622): Wake lock Aquired
W/bt-btif ( 1622): invalid rfc slot id: 8
,D/bt-att  ( 1622): gatt_cleanup_upon_disc 
,D/PMS     (  906): acquireWL(434f69b0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1622 1002 null
D/bt-att  ( 1622): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1622): ATT disconnected
I/bt-smp  ( 1622): SMDBG l2c smp_connect_cback 
D/bt-btm  ( 1622): btm_acl_removed
D/bt-btm  ( 1622): btm_bda_to_acl found
D/bt-btm  ( 1622): btm_acl_report_role_change
D/bt-btm  ( 1622): btm_acl_update_busy_level
D/bt-btm  ( 1622): BTM_BLI_ACL_DOWN_EVT
D/bt-btm  ( 1622): acl hci_handle=2 is_le_link=0 connectable_mode=0x0 link_role=0
D/bt-btm  ( 1622): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1622): Bletooth link down
D/bt-btm  ( 1622): after update p_dev_rec->sec_flags=0xb8
D/bt-btm  ( 1622): btm_acl_resubmit_page
E/bt-btm  ( 1622): btm_sec_disconnected - Clearing Pending flag
I/bt-btm  ( 1622): before Update sec_flags=0xb8
D/bt-btm  ( 1622): btm_ble_update_mode_operation adv_mode = 0
I/bt-btm  ( 1622): after Update sec_flags=0xb8
I/bt-btif ( 1622): bta_jv_free_set_pm_profile_cb(jv_handle: 0x187), idx: 1, app_id: 0xff
D/bt-btm  ( 1622): BTM_ReadRemoteFeatures
D/bt-btm  ( 1622): btm_get_acl_disc_reason_code
I/bt-btif ( 1622): HAL bt_hal_cbacks->acl_state_changed_cb
,D/BluetoothAdapterService(1101640176)( 1622): Get ACL Connected Devices being called
,E/BluetoothAdapterProperties( 1622): setAclConnectedDevices failed to remove device: B0:C5:59:3F:75:69
,D/BluetoothRemoteDevices( 1622): aclStateChangeCallback: State:DisConnected to Device:B0:C5:59:3F:75:69
,V/BluetoothSapReceiver( 1622): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1622): action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapReceiver( 1622): Calling SAP service start service with action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1622): action: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1622): state: -2147483648
,E/BluetoothDevice( 2867): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2867): getBluetoothClass(): COD is 5898764
,I/BTConnectionReceiver( 2867): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2867): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/BTIF_CORE( 1622): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1622): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  906): releaseWL(434f69b0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1622): Wake lock released
,D/PMS     (  906): acquireWL(43b44090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b44090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
,D/ContactMessageStore( 1243): start background delete task...
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  906): acquireWL(44021720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=625560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44021720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43764070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43764070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(441f9058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=685560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441f9058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433b0210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{424ae060: PendingIntentRecord{4402e348 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=712732, Int=300000
,D/PMS     (  906): releaseWL(433b0210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/Process (  906): killProcessQuiet, pid=4336
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4336:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4336
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4247f210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4247f210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43aee648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=745560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43aee648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433353a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41d2ada8: PendingIntentRecord{423b9990 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787390, Int=0
,D/PMS     (  906): releaseWL(433353a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(4329b1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4329b1a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42b016e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=805560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b016e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434f1500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434f1500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44200230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=865560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44200230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  906): acquireWL(441d5330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(441d5330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b050e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=925560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b050e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ab08c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(43ab08c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436856f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436856f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(435aab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435aab48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4350ace0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43f832f0: PendingIntentRecord{423f8050 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010142, Int=0
,D/PMS     (  906): acquireWL(43479830): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1439 10028 null
V/AlarmManager(  906): sending alarm PendingIntent{4200f1d0: PendingIntentRecord{41cc6828 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452272837799, Int=900000
V/AlarmManager(  906): sending alarm PendingIntent{424fd808: PendingIntentRecord{425fd9b0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452272907585, Int=0
,D/PMS     (  906): releaseWL(43479830): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(433ff5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4644): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4644): MY_DEBUG = false
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
D/PMS     (  906): releaseWL(433ff5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(433a7168): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4644 1000 null
,D/PMS     (  906): releaseWL(4350ace0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4338d360): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1439 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4644): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4644): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4644): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4644): SettingOnTime = 1452319200000, randomSettingOnTime = 1452317497000
D/SmartSyncScreenOnOffTimeReceiver( 4644): SettingOffTime = 1452297600000, randomSettingOffTime = 1452302671000
D/SmartSyncScreenOnOffTimeReceiver( 4644): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4644): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4644): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(433a7168): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1439): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1439/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1439/10028)
,D/PMS     (  906): releaseWL(4338d360): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(424bec08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1439 10028 null
,D/PMS     (  906): releaseWL(424bec08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=9 [235][22][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43112990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43112990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b15688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b15688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(433962d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(433962d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f14c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f14c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43a86358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1105560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a86358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bfe4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  906): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43bfe4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42589f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1165560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42589f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439e86b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(439e86b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43a97650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1225560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a97650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428b0110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428b0110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43090b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1285559, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43090b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43af6950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43af6950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430b5ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1345560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430b5ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4323e8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4323e8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(441f53d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1405560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441f53d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435bc9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435bc9a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43a17548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1465560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a17548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424d4c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424d4c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(435d2d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1525560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435d2d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bae558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bae558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434128f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1585560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434128f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4257eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4257eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43b21c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1645560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b21c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a34280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43a34280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424cdbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424cdbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/TetherSettings( 4224): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4224): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4224): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4224): Cust_ConnectToPC   : spcsc>false
D/        ( 4224): Cust_ConnectToPC   : IPT>true
D/        ( 4224): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4224): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4224): Index of the first 1 = 3
W/Settings( 4224): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4224): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4224): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4224): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4224): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4224): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 4224): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  906): acquireWL(431d1a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(431d1a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42b24060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1705560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b24060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a30ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43a30ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42b00788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b00788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4323b3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1765559, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4323b3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43f7a908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43f7a908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43553b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43553b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43357010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1825560, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 36ms
,I/ProcessStatsService(  906): Prepared write state in 21ms
,D/PMS     (  906): releaseWL(43357010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-08-02-24-53.bin
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(43699528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d2ada8: PendingIntentRecord{423b9990 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1507423, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{422b1b38: PendingIntentRecord{424789f8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1822573, Int=1800000
V/AlarmManager(  906): sending alarm PendingIntent{437560f0: PendingIntentRecord{425e3f80 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452272964098, Int=1800000
D/PMS     (  906): acquireWL(429e4cc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{4200f1d0: PendingIntentRecord{41cc6828 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452273737799, Int=900000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(429e4cc8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(43a3cb80): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1222 10028 null
,D/PMS     (  906): acquireWL(43bf9258): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1222 10028 null
,D/PMS     (  906): releaseWL(43a3cb80): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1222): Aggregate from 1452272003231 (log), 1452271164049 (data)
W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43699528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(43bf9258): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(430efc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430efc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4205b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4205b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(432582b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41b37858: PendingIntentRecord{41db5bb8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1885560, Int=0
D/Process (  906): killProcessQuiet, pid=4353
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4353:com.android.settings:remote/1000 (adj 15): empty for 1807s
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432582b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Recipient 4353
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4741): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4741): ====startRecUseTime====
D/htc.customization.log.level( 4741):  is 
W/CustomizationLogLevel( 4741): Level value is invalid, use default level 2
D/CustomizationManager( 4741):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4741): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4741): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4741): Parsing tag category name = system
I/CustomizationCIDLoader( 4741): Parsing tag category name = application
I/CustomizationCIDLoader( 4741): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4741): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4741): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4741): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4741): Parsing tag category name = Settings
D/CustomizationManager( 4741):  Read CID file spent 0.153 (s)
D/CustomizationManager( 4741):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4741): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4741): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4741): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4741): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4741, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4389
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4389:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=4540
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4509
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4489
I/ActivityManager(  906): Killing 4540:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4509:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4489:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3838
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4446
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4187
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 3838:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4446:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1806s
I/ActivityManager(  906): Killing 4187:com.android.vending/u0a73 (adj 15): empty for 1820s
I/ActivityManager(  906):   Force finishing activity ActivityRecord{422f8538 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  906): Recipient 4509
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  906): Copying FileAsset 0x6308cc18 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4446
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4489
I/ActivityManager(  906): Recipient 3838
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3838): Died!
I/ActivityManager(  906): Recipient 4187
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4389 uid 10348
W/PackageSettings(  906): Skipping PackageSetting{42231408 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Recipient 4540
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
W/InputDispatcher(  906): channel '423ab858 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '423ab858 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/bt-btif ( 1622): BTA_JvDeleteRecord
D/bt-sdp  ( 1622): SDP_DeleteRecord ok, num_records:16
I/bt-btif ( 1622): BTA_JvRfcommStopServer
E/bt-btif ( 1622): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1622): BTM_SEC_CLR[19]: id 58
D/bt-btm  ( 1622): BTM_FreeSCN 
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '423ab858 com.test.thalitest.MainActivity (s)'
I/WindowState(  906): WIN DEATH: Window{423ab858 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1493): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1868): Unregistering com.test.thalitest
E/acms    ( 1868): Could not unregister removed application com.test.thalitest
I/WindowManager(  906): WINDOW DIED Window{423ab858 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PMS     (  906): acquireWL(43a8bb00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1493 10028 null
D/PMS     (  906): releaseWL(43a8bb00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/dalvikvm-heap( 4119): Grow heap (frag case) to 13.499MB for 1821008-byte allocation
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/PackageBroadcastService( 1222): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4756 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4756): install
I/MultiDex( 4756): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/ActivityManager(  906): Delaying start of: ServiceRecord{424e1268 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4756): loading existing secondary dex files
I/MultiDex( 4756): load found 1 secondary dex files
I/MultiDex( 4756): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4772 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PeopleContactsSync( 1222): CP2 sync disabled
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1222, uid=10028, userID:0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Scheme: "mmsto"
I/ProviderInstaller( 4756): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): acquireWL(43be69b0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
I/Icing   ( 1222): doRemovePackageData com.test.thalitest
I/MultiDex( 4772): install
I/MultiDex( 4772): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  906): releaseWL(43be69b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4772): loading existing secondary dex files
I/MultiDex( 4772): load found 1 secondary dex files
I/MultiDex( 4772): install done
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4772): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(43a94160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{42d6dda0: PendingIntentRecord{423f8050 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1913266, Int=0
I/[PluginManager]RegisterService( 1392): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1392): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4791 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=4119
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4119:com.google.android.apps.plus/u0a160 (adj 15): empty for 1803s
I/ActivityManager(  906): Recipient 4119
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4791, uid=10073, userID:0
D/Finsky  ( 4791): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4791/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4791/10073)
E/SQLiteLog( 4756): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4756): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9d4ca0
E/DriveAsyncService( 4756): disk I/O error (code 3850)
E/DriveAsyncService( 4756): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4756): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4756): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4756): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4756): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4756): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4756): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4756): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4756): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4756): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4756): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9d4ca0
E/DocListDatabase( 4756): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4756): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4756): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4756): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4756): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4756): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4756): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4756): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4756): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4756): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4756): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4756): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4756): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4756): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4756): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4756): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4756): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4756): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4756): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4756): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4756): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4756): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4756): threadid=1: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 4756): FATAL EXCEPTION: main
E/AndroidRuntime( 4756): Process: com.google.android.gms.drive, PID: 4756
E/AndroidRuntime( 4756): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4756): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4756): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4756): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4756): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4756): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4756): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4756): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4756): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4756): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4756): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4756): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4756): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4756): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4756): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4756): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4756): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4756): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4756): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4756): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4756): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4756): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4756): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4756): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4756): killProcess, pid=4756
D/Process ( 4756): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
D/Finsky  ( 4791): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4791): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4791): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4791): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4791): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4791): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4791): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4791): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4791): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4791): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4791): threadid=25: thread exiting with uncaught exception (group=0x4164fe30)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4791, uid=10073, userID:0
E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 4791): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4791): Process: com.android.vending, PID: 4791
E/AndroidRuntime( 4791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4791): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4791): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4791): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4791): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4791): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4791): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 4791): killProcess, pid=4791
D/Process ( 4791): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4756
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4756) has died.
I/IcingCorporaProvider( 2867): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4830 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2867): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2867): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63a638f8
W/dalvikvm( 2867): threadid=14: thread exiting with uncaught exception (group=0x4164fe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2867): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2867): Process: com.google.android.googlequicksearchbox:search, PID: 2867
E/AndroidRuntime( 2867): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2867): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2867): 	at cid.d(PG:186)
E/AndroidRuntime( 2867): 	at clo.g(PG:594)
E/AndroidRuntime( 2867): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2867): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2867): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2867): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2867): 	at clr.tL(PG:827)
E/AndroidRuntime( 2867): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2867): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2867): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2867): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Recipient 4791
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process ( 2867): killProcess, pid=2867
D/Process ( 2867): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Process com.android.vending (pid 4791) has died.
F/ProcessStats(  906): Starting service ServiceState{43abbc98 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=43abbc98} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  906): Recipient 2867
D/WifiService(  906): Client connection lost with reason: 4
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2867): Died!
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452273808338.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  906): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  906): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4131)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ErrorReport(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 18 more
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2867) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10778ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20778ms
I/TrimMemoryManager( 1269): [trimMemory] 5
F/ProcessStats(  906): Starting service ServiceState{424d1d90 com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService pkg=com.google.android.googlequicksearchbox proc=424d1d90} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452273808393.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  906): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  906): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16827)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16804)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1897)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1846)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.serviceDoneExecuting(ActivityManagerService.java:13937)
E/ErrorReport(  906): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:919)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 23 more
F/ProcessStats(  906): Starting service ServiceState{43abbc98 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=43abbc98} without owner
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452273808417.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  906): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  906): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16827)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16804)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1897)
E/ErrorReport(  906): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1846)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.serviceDoneExecuting(ActivityManagerService.java:13937)
E/ErrorReport(  906): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:919)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 23 more
W/PackageManager(  906): Unable to load service info ResolveInfo{423a0ec8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b12e70 +
I/Prism.WidgetManager( 1269): onLoadItems() +
E/SQLiteDatabase( 4830): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4830): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4830): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4830): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4830): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4830): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4830): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4830): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4830): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4830): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4830): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4830): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4830): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4830): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4830): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4830): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4830): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4830): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4830): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4830): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4830): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4830): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4830): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4830): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4830): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4830): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4830): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4830): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4830): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4830): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4830): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4830): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4830): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4830): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4830): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4830): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4830): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4830): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4830): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4830): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4830): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4830): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4830): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4830): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4830): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4830): threadid=11: thread exiting with uncaught exception (group=0x4164fe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4830): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4830): Process: com.google.android.apps.docs, PID: 4830
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
E/AndroidRuntime( 4830): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4830): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4830): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4830): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4830): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4830): killProcess, pid=4830

```
