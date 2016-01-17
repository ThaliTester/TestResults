#### Test 5615109389cecbd_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
--------- beginning of /dev/log/system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{43eed768 u0 com.htc.htclocationservice/.AutoSettingService}
,E/cutils-trace( 4629): Error opening trace file: No such file or directory (2)
I/SensorManager(  905): mEventCount = 1050
V/LightsService(  905): setLight #0: color=#3f
D/CustomizationManager( 4629): ====startRecUseTime====
D/htc.customization.log.level( 4629):  is 
W/CustomizationLogLevel( 4629): Level value is invalid, use default level 2
V/LightsService(  905): setLight #0: color=#3c
V/LightsService(  905): setLight #0: color=#35
D/CustomizationManager( 4629):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4629): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4629): full path : /system/customize/CID/HTC__032.xml
V/LightsService(  905): setLight #0: color=#2f
I/CustomizationCIDLoader( 4629): Parsing tag category name = system
I/CustomizationCIDLoader( 4629): Parsing tag category name = application
I/CustomizationCIDLoader( 4629): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4629): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4629): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4629): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4629): Parsing tag category name = Settings
D/CustomizationManager( 4629):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4629):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4629): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4629): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4629): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4629): Fail to get flag for type 'language', use default value: -1
V/LightsService(  905): setLight #0: color=#28
V/LightsService(  905): setLight #0: color=#21
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4629
D/PMS     (  905): acquireHCC(42351378): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(41e6cc40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x6bbcfae0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1111733864
D/PMS     (  905): acquireWL(43538d28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1276): [onPause]
I/FeedProviderManager( 1276): onPause
I/FeedHostManager( 1276): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41be5450
I/SocialFeedProvider( 1276): +onPause
I/SocialFeedProvider( 1276): -onPause
V/LightsService(  905): setLight #0: color=#17
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4641 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
V/LightsService(  905): setLight #0: color=#14
I/TrimMemoryManager( 1276): [trimMemory] 20
W/asset   ( 4641): Copying FileAsset 0x5c831428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4641): Binding Chromium to main looper Looper (main, tid 1) {41b02310}
I/LibraryLoader( 4641): Expected native library version number "",actual native library version number ""
I/chromium( 4641): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4641): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(42589550): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(42517398): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(42589550): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42514368:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4641): 1102150984: getState(). Returning 12
I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4641): Local Branch: 
I/Adreno-EGL( 4641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4641):                  aa63bbd948f41d15fc72f585e
W/chromium( 4641): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4641): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4641): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4641): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4641): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4641): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4641): CordovaWebView is running on device made by: HTC
,W/AwContents( 4641): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1276
W/ResourceType( 4641): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4641): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b493f8, mServedView=org.apache.cordova.engine.SystemWebView{41b0f060 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +294ms
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=4641
W/AwContents( 4641): nativeOnDraw failed; clearing to background color.
D/PMS     (  905): releaseWL(43538d28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4641): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4641): JniHelper::setJavaVM(0x415d4048), pthread_self() = 1663081344
D/JX-Cordova( 4641): jxcore cordova android initializing
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 12.028MB for 63974-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 12.081MB for 95956-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 12.159MB for 143930-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 12.275MB for 215890-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 12.446MB for 323830-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 13.120MB for 728606-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 13.714MB for 1092904-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 14.631MB for 1639352-byte allocation
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 15.952MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(42351378): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(41e6cc40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 18.067MB for 3688532-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/jxcore-log( 4641): Initializing JXcore engine
,W/jxcore-log( 4641): JXcore engine is ready
,W/jxcore-log( 4641): Starting JXcore engine
,W/jxcore-log( 4641): Platform android
W/jxcore-log( 4641): 
,W/jxcore-log( 4641): Process ARCH arm
W/jxcore-log( 4641): 
,D/PMS     (  905): releaseWL(42517398): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4641): JXcore Cordova bridge is ready!
I/jxcore-log( 4641): 
,W/jxcore-log( 4641): JXcore engine is started
,I/chromium( 4641): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4641): Toggling radios to true
I/jxcore-log( 4641): 
,D/BluetoothAdapter( 4641): enable(): BT is already enabled..!
,D/WifiManager( 4641): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4641, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1482
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 8(ms)
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4641): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4641): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): TDLS: Tear down peers
I/wpa_supplicant( 1159): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4641): Radios toggled
I/jxcore-log( 4641): 
I/jxcore-log( 4641): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4641): 
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1159): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1159): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1159): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7b37bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1159):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1159): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1159): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_suppl,icant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  905): acquireWL(4357f128): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): Fast associate: Old scan results
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20279 mDataStallAlarmIntent=PendingIntent{41c67918: PendingIntentRecord{4258d300 android broadcastIntent}}
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WISPrService( 4238): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4238): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1361): Read error: ssl=0x65878670: I/O error during system call, Connection timed out
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:4   entry:0xb8a68cd8  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8a5faf8  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8a68db8  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8a642e8  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8a641b8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8a68f70  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8a5fc20  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8a64458  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb8a648d0  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WISPrService( 4238): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4238): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I//system/bin/ip(  365): RTNETLINK answers: No such process
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  905): acquireWL(434fdf70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x65878670: I/O error during system call, Broken pipe
D/PMS     (  905): acquireWL(434e61d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
D/PMS     (  905): releaseWL(434fdf70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  905): releaseWL(434e61d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4693 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(41bf19b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(41bf19b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4490/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4490/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,I/MusicStore( 4693): Database version: 95
,W/ContextImpl( 4693): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4693): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4693): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4693): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4693): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4693, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4693): Registered
,I/MediaRouter( 4693): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4693/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1978/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4713 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4693): getSelectedRoute
,I/NetworkMonitor( 4693): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4693/10154)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4693, uid=10154, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42d6e130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42d6e130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  905): killProcessQuiet, pid=4404
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4404:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/ACRA    ( 4713): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4713): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4713): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4713): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4713): Preparing secondary program dexes.
V/DexLibLoader( 4713): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4713): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4713): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4713): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4713): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4713): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4713): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4713): Dex already copied
D/OdexVerifier( 4713): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4713): Creating class loader
,V/DexLibLoader( 4713): Finished creating class loader
V/DexLibLoader( 4713): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4713): Dex already copied
D/OdexVerifier( 4713): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4713): Creating class loader
,V/DexLibLoader( 4713): Finished creating class loader
V/DexLibLoader( 4713): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4713): Dex already copied
D/OdexVerifier( 4713): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4713): Creating class loader
,V/DexLibLoader( 4713): Finished creating class loader
V/DexLibLoader( 4713): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4713): Dex already copied
D/OdexVerifier( 4713): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4713): Creating class loader
,V/DexLibLoader( 4713): Finished creating class loader
,V/DexLibLoader( 4713): Verifying classes from secondary dexes.
,D/DexLibLoader( 4713): DexLibLoader.ensureDexLoaded took 16 ms
I/ActivityManager(  905): Recipient 4404
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4713): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4713): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1159): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1159): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1159): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 3
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 1
I/wpa_supplicant( 1159): wpa_s->is_screen_on 1
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): selected network = 2
D/wpa_supplicant( 1159): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7b394e8  current_ssid=0x0
D/wpa_supplicant( 1159),: wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1159): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1159): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1159): check if in concurrent case
I/wpa_supplicant( 1159): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1159): RSN: PMKSA cache search - network_ctx=0xb7b394e8 try_opportunistic=0
D/wpa_supplicant( 1159): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1159): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1159): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1159): nl80211: Unsubscribe mgmt frames handle 0xb7b38718 (mode change)
D/wpa_supplicant( 1159): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b38718
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb7b38718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1159):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159):   * freq=2412
D/wpa_supplicant( 1159):   * Auth Type 0
D/wpa_supplicant( 1159):   * WPA Versions 0x2
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1159): nl80211: Connect request send successfully
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant p,ort unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (636) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000022370612
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-51
I/wpa_supplicant( 1159): tsf=0000000106941131
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-51
I/wpa_supplicant( 1159): tsf=0000000106941135
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2427
I/wpa_supplicant( 1159): level=-78
I/wpa_supplicant( 1159): tsf=0000000106941139
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000106941143
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=UPC4688432
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 22370612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 106941131, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 106941135, distance: ?(cm), distanceSd: ?(cm)
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiManager( 1228): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 106941139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 106941143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Connect event
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1159): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Add randomness: count=13 entropy=5
I/wpa_supplicant( 1159): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1159): TDLS: Remove peers on association
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1159): EAPOL: enable timer tick
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): Get randomness: len=32 entropy=6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7b389f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1159):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fbeb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1159):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1159): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1159): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1159): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1159): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1159): set send_ind_to_ndc = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1159): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1159): EAPOL authentication completed successfully
I/wpa_supplicant( 1159): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): This record is existed, only update it...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
W/dalvikvm( 4713): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4238): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4238): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 1
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(442ec680): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42520068 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42520068 target=com.android.internal.util.StateMachine$SmHandler }
W/dalvikvm( 4713): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,E/FbInjectorInitializer( 4713): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4713): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4713): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4713): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4183
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4183:com.google.android.gm/u0a107 (adj 15): empty #17
,D/AutoSetting( 1304): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4742 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
,D/AutoSetting( 1304): Util - no network available!
,D/AutoSetting( 1304): service - onCreate()
,D/AutoSetting( 1304): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  905): request 4253aee0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/AutoSetting( 1304): service - mHandler: cancel location update
D/AutoSetting( 1304): service -           changes count: 0
,I/ActivityManager(  905): Recipient 4183
,D/MobileConnectivityChangeReceiver( 4742): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4742): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4742): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4742): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4757 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4742/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4742/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4742/10079)
,W/fb4a(:<default>):UserScope( 4713): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4713): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4713): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f9058
,W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f9058, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b0ea48
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4269b5d8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4772 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4424
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4424:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4424
,D/WifiService(  905): Client connection lost with reason: 4
,E/dalvikvm( 4713): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4713): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4713): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4713): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4713): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4713): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4713): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4713): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4713): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4713): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4713): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4713): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4713): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4713): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4713): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4713): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4713): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4713): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 9.997MB for 79892-byte allocation
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 10.062MB for 84664-byte allocation
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 10.089MB for 28144-byte allocation
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438a9a80 u0 ReceiverList{438a9960 4713 com.facebook.katana/10027/u0 remote:43885788}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438a9a80 u0 ReceiverList{438a9960 4713 com.facebook.katana/10027/u0 remote:43885788}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e4d048 u0 ReceiverList{43e4cfe8 4713 com.facebook.katana/10027/u0 remote:43e33068}}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 314ms
D/wpa_supplicant( 1159): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1159): EAPOL: disable timer tick
D/PMS     (  905): nativeSetInteractive:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/NfcService( 1259): ScreenObserver: OFF
D/NfcService( 1259): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425f71a0)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/InputMethodManagerService(  905): Disable input method client, pid=4641
D/PMN     (  905): wakingUp
I/WindowManager(  905): No lock screen! windowToken=null
,D/NfcService( 1259): applyRouting -2
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(42d32680): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  905): releaseWL(42d32680): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): onScreenOn
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): acquireWL(43eee500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42691b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42691b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1573): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 1978): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1978): [MTP][onReceive]-
D/NfcService( 1259): applyRouting - 0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/NfcService( 1259): applyRouting -2
,W/GAV2    ( 4772): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  905): acquireWL(44325670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43eee500): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4772): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): releaseWL(44325670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4772): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ClockThread( 1117): stop update clock
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4772): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4772): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4713): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4713): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4713): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4641): 
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4772/10151)
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/WebViewChromiumFactoryProvider( 4772): Binding Chromium to main looper Looper (main, tid 1) {41afbd38}
,I/LibraryLoader( 4772): Expected native library version number "",actual native library version number ""
,I/chromium( 4772): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4772): Initializing chromium process, renderers=0
D/NetworkPolicy(  905): updateScreenOn: false
,D/PMS     (  905): acquireWL(438192e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  905): acquireWL(4349f868): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4772): BLUETOOTH permission is missing!
D/PMS     (  905): releaseWL(438192e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4772): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4772): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4772): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4772): Local Branch: 
I/Adreno-EGL( 4772): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4772): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4772):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  905): acquireWL(436f6eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436f6eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1573): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43717cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,I/NSApplication( 4772): Starting up...
D/PMS     (  905): releaseWL(43717cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4772/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4772/10151)
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1780): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): onScreenOn: 1453023971851
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1780): onScreenOn: 1453023971852
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b0ea48
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b0ea48, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4269b5d8
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4213/10160)
D/PMN     (  905): goingToSleep
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4213/10160)
D/PMS     (  905): acquireWL(42856d08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
D/Process (  905): killProcessQuiet, pid=4301
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
I/ActivityManager(  905): Killing 4301:com.google.android.talk/u0a111 (adj 15): empty #17
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20280 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1159): get_ip_address source addr = 02000000
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
I/iu.Environment( 2115): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 2115): num queued entries: 0
V/SRS_Proc(  372): ParamSet string: screen_state=off
I/iu.UploadsManager( 2115): num updated entries: 0
,I/iu.SyncManager( 2115): NEXT; no task
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(4385f198): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(4385f198): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/AutoSetting( 1304): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/TetherSettings( 4238): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4238): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4238): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4238): Cust_ConnectToPC   : spcsc>false
D/        ( 4238): Cust_ConnectToPC   : IPT>true
,D/        ( 4238): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4238): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4238): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4238): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4238): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4238): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4238): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4238): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4238):  defaultType:0
W/ContextImpl( 4238): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Recipient 4301
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(442af778): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(442af778): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43e71398): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1573): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  905): releaseWL(43e71398): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1780): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1780): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1780): onScreenOff
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4831 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AutoSetting( 1304): service - mHandler: cancel location update
,D/AutoSetting( 1304): service -           changes count: 0
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4831): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(434a04b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4831 1000 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(434a04b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4831): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4831): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4831): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4831): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269b5d8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269b5d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269b5d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269b5d8
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42704ad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42704ad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/Process (  905): killProcessQuiet, pid=4459
,I/ActivityManager(  905): Killing 4459:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4459
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4641): 
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4641): 
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(442ec680): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4641): 
W/ActivityManager(  905): Activity pause timeout for ActivityRecord{424810b8 u0 com.test.thalitest/.MainActivity t2}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4238): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42483518
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4641): 
,I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4641): 
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
I/jxcore-log( 4641): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4641): 
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(442af940): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4742/10079)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(43f230d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43f1b330): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2115): Checkin interval check for package: unspecified last checkin: 1453023922690 min interval config: 0 actual interval: 49773
D/PMS     (  905): releaseWL(43f230d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2115): Checking schedule, now: 1453023972473 next: 1453023952657
,I/CheckinService( 2115): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2115, uid=10029, userID:0
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(442af940): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinService( 2115): Preparing to send checkin request
,I/EventLogService( 2115): Accumulating logs since 1453023918798
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,I/CheckinRequestBuilder( 2115): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2115): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2115/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4885 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4885): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4885): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4885): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4885): install
,I/MultiDex( 4885): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4885): loading existing secondary dex files
,I/MultiDex( 4885): load found 3 secondary dex files
,I/MultiDex( 4885): install done
,W/dalvikvm( 4885): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4885): VFY: unable to resolve instance field 36
,W/dalvikvm( 4885): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4885): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4885): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4885): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4885): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1228): callingUid 10029, callindPid: 1228
,W/dalvikvm( 4885): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4885): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4885): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4885): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
W/dalvikvm( 4885): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2115): Restart initialization of location
,E/MDM     ( 1228): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
,I/jxcore-log( 4641): Test app app.js loaded
I/jxcore-log( 4641): 
D/PMS     (  905): acquireWL(42570d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,I/Choreographer( 4641): Skipped 287 frames!  The application may be doing too much work on its main thread.
D/PMS     (  905): releaseWL(42570d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,W/ResourceType( 4641): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4641): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b0f060 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4641): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  905): releaseWL(42856d08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4885): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2969301475
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4885/10029)
,I/Adreno-EGL( 4885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4885): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4885): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4885): Local Branch: 
I/Adreno-EGL( 4885): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4885): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4885):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  905): releaseWL(4357f128): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(41ecae68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(41ecae68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  905): NoActiveNetworkState
I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4693/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4490/10100)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/NetworkMonitor( 4693): type=WIFI subType= reason=null isConnected=true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4742/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (4002/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42ed6650): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4490/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,I/WVCdm   (  372): CdmEngine::OpenSession
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
D/PMS     (  905): releaseWL(42ed6650): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1978/10021)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1304): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/MobileConnectivityChangeReceiver( 4742): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4742): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1304): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1304): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1304): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4772/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4213/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4213/10160)
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1708365230
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2115): Checkin interval check for package: unspecified last checkin: 1453023922690 min interval config: 0 actual interval: 50873
D/PMS     (  905): acquireWL(438d8068): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(438d8068): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4213): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2115, uid=10029, userID:0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,I/iu.Environment( 2115): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2115): num queued entries: 0
,I/iu.UploadsManager( 2115): num updated entries: 0
,I/iu.SyncManager( 2115): NEXT; no task
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  905): acquireWL(4421d338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fa89 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 219
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): acquireWL(43879810): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): releaseWL(4421d338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(43879810): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42e3ee40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(42e3ee40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,W/Settings( 4885): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/fb4a(:<default>):UserScope( 4713): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4713): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=22 [9][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,I/Adreno-EGL( 4885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4885): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4885): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4885): Local Branch: 
I/Adreno-EGL( 4885): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4885): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4885):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4885): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4885): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4885): Local Branch: 
I/Adreno-EGL( 4885): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4885): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4885):                  aa63bbd948f41d15fc72f585e
,E/fb4a(:<default>):LocalFbBroadcastManager( 4713): Called registerBroadcastReceiver twice.
I/CheckinRequestBuilder( 2115): Classify the device as Phone.
,D/libc    ( 2115): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2115): [NET] getaddrinfo-,err=8
,D/libc    ( 2115): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2115): [NET] getaddrinfo-, 1
,D/libc    ( 2115): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d9d6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2115): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2115): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2115): [NET] getaddrinfo-,err=8
,D/libc    ( 4713): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4713): [NET] getaddrinfo-,err=8
D/libc    ( 4713): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4713): [NET] getaddrinfo-, 1
,D/libc    ( 4713): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =118f +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 38
D/libc    (  365): [NET]res_nsend:resplen=74
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4713): [NET] getaddrinfo_proxy-, success
I/global  ( 4713): call createSocket() return a new socket.
D/libc    ( 4713): [NET] getaddrinfo+,hn 12(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4713): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2115): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2115): [NET] getaddrinfo-,err=8
D/libc    ( 2115): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2115): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/CheckinTask( 2115): Sending checkin request (12207 bytes)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=7 [14][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/libc    ( 4713): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4713): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(42ab0828): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4693 10154 null
,W/ContextImpl( 4693): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4693, uid=10154, userID:0
,I/MusicLeanback( 4693): Conditions not met for autocaching.
,I/MusicLeanback( 4693): Stop autocaching.
D/PMS     (  905): releaseWL(42ab0828): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4693): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/dalvikvm-heap( 4713): Grow heap (frag case) to 11.009MB for 32784-byte allocation
,I/CheckinRequestBuilder( 2115): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2115): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  905): acquireWL(43e489c8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4713 10027 null
,D/PMS     (  905): releaseWL(4349f868): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027),
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4713/10027)
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2115/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=21 [23][5][0]
,I/CheckinRequestBuilder( 2115): Classify the device as Phone.
,I/CheckinTask( 2115): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2115): Checking schedule, now: 1453023975013 next: 1453546912008
,I/CheckinService( 2115): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2115, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,I/CheckinService( 2115): Checking schedule, now: 1453023975051 next: 1453546912008
I/CheckinService( 2115): active receiver: disabled
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2115, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
D/CheckinService( 2115): Recording last checkin time for package unspecified as 1453023975060
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/PMS     (  905): releaseWL(43f1b330): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2115/10029)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4146 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 6
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,I/global  ( 4713): I/O error closing connection
I/global  ( 4713): java.net.SocketException: Socket is closed
I/global  ( 4713): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4713): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4713): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4713): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4713): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4713): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4713): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4713): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4713): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4713): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4713): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4713): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4713): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4713): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4713): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4713): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4713): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4713): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4713): Removing a connection that never existed!
D/PMS     (  905): releaseWL(43e489c8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4772): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1527): service - handleMessage() stop self
,D/AutoSetting( 1527): service - onDestroy() END
,D/AutoSetting( 1527): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4490
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4490:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4490
,D/Process (  905): killProcessQuiet, pid=4513
,I/ActivityManager(  905): Killing 4513:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4513
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4942 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4942): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4942): MmsConfig.loadMmsSettings
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4965 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,W/dalvikvm( 4942): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4942): VFY: unable to resolve instance field 36
,W/dalvikvm( 4942): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4942): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4942, uid=10111, userID:0
,W/Settings( 4942): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4942, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4942, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4942, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4942, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4942, uid=10111, userID:0
,D/PMS     (  905): acquireWL(434f69f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4942 10111 null
,D/MessageFrequencyProvider( 4965): onCreate
,V/GetPrviateResource( 4965): GetPrviateResource
,D/MmsCustomizationProvider( 4965): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4965): GetPrviateResource
I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/MmsCustomizationProvider( 4965): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Babel   ( 4942): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4942): MmsConfig.loadFromDatabase
,E/Babel   ( 4942): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4942): MmsConfig.loadFromResources
D/PMS     (  905): acquireWL(43d2c290): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4942): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4942): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  905): releaseWL(43d2c290): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42ad8eb0): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(434f69f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  905): killProcessQuiet, pid=4477
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4477:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/PackageManager(  905): Unable to load service info ResolveInfo{439de9a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ProviderInstaller( 4942): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  905): Recipient 4477
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 4965): sense_version=6.0
,D/BTAccessoryUtil( 4965): createReceiver
,D/BTAccessoryUtil( 4965): registerReceiver return intent = null
D/MessageCustFlag( 4965): sku_id=99
,W/SystemReader( 4965): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4965): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4965): networkCode: 
,D/MessageCustFlag( 4965): sku_id=99
D/MmsConfig( 4965): SIE smsPri: null
,D/MmsConfig( 4965): networkCode: 
,D/HtcTelephonyCapability( 4965): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4965): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4965): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4965): Cannot find qct_8960_interface, use default value instead
,D/Process (  905): killProcessQuiet, pid=4002
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4002:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4002
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(42ad8eb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43a0bcf0): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42750dc8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4213 10160 null
,I/dalvikvm-heap( 4213): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  905): releaseWL(42750dc8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  905): releaseWL(43a0bcf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,I/dalvikvm-heap( 4213): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
D/PMS     (  905): acquireWL(42675330): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42675330): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43e78c78): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  905): releaseWL(43e78c78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  905): acquireWL(44377d00): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44377d00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43299fd0): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43299fd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/PackageBroadcastService( 2115): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2115): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  905): acquireWL(4497c700): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2115): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(424a3238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(424a3238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(424c19b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(424c19b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423f3348): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(423f3348): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 569 ms] updated apps [took 569 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8fbd0 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/Icing   ( 2115): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8fbd0 -
,I/Icing   ( 2115): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(4497c700): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/Messaging( 4965): mNeedToUpdateDate2 start
,D/MmsConfig( 4965): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4965): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4965): 
D/MmsAsyncWorkHandler( 4965): HM tk = 20001
,D/ReportIndicatorCache( 4965): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4965): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b09578
,I/Messaging( 4965): mccmnc> 
D/DraftCache( 4965): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4965): [DraftCache/1] refresh
,D/MmsConfig( 4965): networkCode: 
,D/Messaging( 4965): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4965): HtcWrapEnvironment.getSupportedStorages() >1
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/PhoneStorageUtil( 4965): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4965): createReceiver
,D/MmsSmsV2Provider( 1244):  phoneType = -1
D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4965): sense_version=6.0
,D/Jerry   ( 4965): start to preload cursor >>>>>>>
D/TelephUtils( 1244): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1244): Update uri=content://mms, match=0
,V/MmsProvider( 1244): selection=st=129 AND m_type!=134
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4965): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4965): TransactionService is going to be woken up.
V/TransactionService( 4965): 1-Creating TransactionService
,D/Messaging( 4965): mNeedToUpdateDate2: false
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/TransactionService( 4965): onStartCommand: 1
,D/MmsSystemEventReceiver( 4965): unRegisterForConnectionStateChanges
V/TransactionService( 4965): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4965): Loading previous transactions.
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/DraftCache( 4965): [DraftCache/496] rebuildCache
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1244): device_type: 1
,D/Messaging( 4965): ViewCache CreatePreload
,D/Messaging( 4965): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TransactionService( 4965): Force set service start id to 1
,V/TransactionService( 4965): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4965): unRegisterForConnectionStateChanges
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1244):  phoneType = -1
D/TransactionService( 4965): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4965): Destroying TransactionService
D/Cust_MMSMS( 4965): _has_set_default_values_2=true
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4965): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1244): URI_DRAFT
,D/Messaging( 4965): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4965): def_index: 0
,D/DraftCache( 4965): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4965): [DraftCache/496] rebuildCache time: 1
D/MmsAsyncWorkHandler( 4965): 
D/MmsAsyncWorkHandler( 4965): HM tk = 20002
,D/MsgPreferenceUtils( 4965): globalIndex = 1
D/MsgPreferenceUtils( 4965): phone state: true
D/MsgPreferenceUtils( 4965): sd state: false
,D/MsgPreferenceUtils( 4965): vIndex = 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1244): sku_id=99
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43dad300 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4942): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(42521758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43a118d8: PendingIntentRecord{42a150f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124454, Int=0
,D/PMS     (  905): acquireWL(425571e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42521758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=10 [19][2][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(426aeeb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426aeeb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425571e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42270ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(42270ef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41f6a350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(4243cd40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425593a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1228): Vacuum at: now=1453023988268 tag=VacuumService
D/PMS     (  905): releaseWL(41f6a350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4243cd40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4240e8d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(4240e8d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425593a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41b0ef20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(41b0ef20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(436f17a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(436f17a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4255f270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(4255f270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(44257dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(425adec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425adec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42624620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44257dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(41cd32c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(41cd32c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 6904 seconds from now (1453023988963)
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
D/libc    ( 1228): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7bc7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 254
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(42624620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43e5b080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(43e5b080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43e1b090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(43e1b090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42641890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1573): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42641890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41f39170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41f39170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(438a5ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42493eb0: PendingIntentRecord{42ae0bb8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138516, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): releaseWL(438a5ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): service - has update message, not stop
,D/AutoSetting( 1304): service - mHandler: update timezone
,D/AutoSetting( 1527): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1527): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1527): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1527): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1527): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
D/DotMatrix( 1573): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1527): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1527): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1527): service - mHandler: update timezone
,D/DotMatrix( 1573): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1527): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1527): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1527): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1527): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1573): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1573): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e83c60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 9 2 11
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  905): acquireWL(43988a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42490510: PendingIntentRecord{424ca950 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141953, Int=0
D/PMS     (  905): acquireWL(43f1a4c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43988a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c3e9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(43f1a4c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43a0bbb8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(4370d538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42090590: PendingIntentRecord{42028a10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=156425, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4370d538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1304): service - handleMessage() stop self
,D/AutoSetting( 1304): service - onDestroy() END
,D/AutoSetting( 1304): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4529
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4529:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4529
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1527): service - handleMessage() stop self
,D/AutoSetting( 1527): service - onDestroy() END
,D/AutoSetting( 1527): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4563
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4563:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4563
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(42669650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): releaseWL(42669650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1573): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(432b4998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(432b4998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43c38498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42090590: PendingIntentRecord{42028a10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=216424, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c38498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42723038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{425873e8: PendingIntentRecord{43bbbee8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228175, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5050 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{426e5818: PendingIntentRecord{426a3890 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453024077050, Int=10800000
,D/PMS     (  905): releaseWL(42723038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (5050/10049)
,D/PMS     (  905): acquireWL(43370920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{4269bf98: PendingIntentRecord{42678170 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=228178, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{42d941d0: PendingIntentRecord{43bbbee8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228312, Int=0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/PMS     (  905): releaseWL(43370920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025321
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025463
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025471
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025474
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027342
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027355
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029587
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032164
,D/Process (  905): killProcessQuiet, pid=4578
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4578:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4578
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43171bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43171bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(438d8a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438d8a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1573): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1573): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4320e9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42090590: PendingIntentRecord{42028a10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=276424, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4320e9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(426e1440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426e1440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4641): --= Surplus to requirements =--
I/jxcore-log( 4641): 
,I/jxcore-log( 4641): ****TEST TOOK:  ms ****
I/jxcore-log( 4641): 
,I/jxcore-log( 4641): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4641): 
,E/cutils-trace( 5072): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5072): ====startRecUseTime====
D/htc.customization.log.level( 5072):  is 
,W/CustomizationLogLevel( 5072): Level value is invalid, use default level 2
,D/CustomizationManager( 5072):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5072): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 5072): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5072): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5072): Parsing tag category name = system
,I/CustomizationCIDLoader( 5072): Parsing tag category name = application
I/CustomizationCIDLoader( 5072): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5072): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 5072): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5072): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5072): Parsing tag category name = Settings
D/CustomizationManager( 5072):  Read CID file spent 0.162 (s)
,D/CustomizationManager( 5072):  All configurations done spent 0.162 (s)
,W/HtcNativeFlag( 5072): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5072): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5072): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 5072): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=5072, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4641
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4641:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{424810b8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x69a5f318 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4641 uid 10389
,W/PackageSettings(  905): Skipping PackageSetting{4221baf8 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/WindowState(  905): WIN DEATH: Window{4258eb58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1573): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1573): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1573): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  905): acquireWL(43df1e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): releaseWL(43df1e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/SQLiteConnectionPool( 2115): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsRemoved
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1276): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5087 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(43e66ed0): PARTIAL_WAKE_LOCK  Icing 0x1 2115 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 373 ms] updated apps [took 373 ms] 
,E/SQLiteDatabase( 5087): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5087): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5087): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5087): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5087): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5087): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5087): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5087): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5087): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5087): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5087): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5087): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5087): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5087): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5087): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5087): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5087): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5087): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5087): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5087): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5087): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5087): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5087): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5087): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5087): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5087): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5087): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5087): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5087): 	,at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5087): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5087): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5087): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5087): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5087): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5087): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5087): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5087): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5087): ,	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5087): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5087): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5087): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5087): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5087): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5087): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5087): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5087): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5087): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5087): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5087): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5087): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5087): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 5087): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5087): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5087): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5087): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5087): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5087): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 5087): threadid=11: thread exiting with uncaught exception (group=0x416cce30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5087): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5087): Process: com.google.android.apps.docs, PID: 5087
E/AndroidRuntime( 5087): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5087): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5087): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5087): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5087): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5087): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5087): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5087): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5087): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 5087): killProcess, pid=5087
,D/Process ( 5087): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5106 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Recipient 5087
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 5087) has died.
,W/ContextImpl( 5106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5119 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5106): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5106): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5106): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5106): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5106): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5106): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5106): threadid=10: thread exiting with uncaught exception (group=0x416cce30)
,E/AndroidRuntime( 5106): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5106): Process: com.android.keychain, PID: 5106
E/AndroidRuntime( 5106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5106): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5106): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5106): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5106): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5106): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
,D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 5119): getInstance(Context context),
,D/AppTag  ( 5119): getInstance(Context context)
,D/AppTag  ( 5119): onCreate()
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(4249ec70): PARTIAL_WAKE_LOCK  AsyncService 0x1 4213 10160 null
,D/Process ( 5106): killProcess, pid=5106
,D/Process ( 5106): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/PMS     (  905): releaseWL(4249ec70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  905): acquireWL(41da3430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
I/ActivityManager(  905): Resuming delayed broadcast
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453024199995.dbox_tmp: open failed: EROFS (Read-only file system)
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
V/AlarmManager(  905): sending alarm PendingIntent{42090590: PendingIntentRecord{42028a10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=336425, Int=0
,I/ActivityManager(  905): Recipient 5106
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 5106) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/Process (  905): killProcessQuiet, pid=4612
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 4612:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
W/dalvikvm( 4256): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4612
,D/PackageBroadcastService( 2115): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2115): Clearing selected account for com.test.thalitest,
,D/ChimeraCfgMgr( 2115): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2115): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2115): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2115): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2115): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2115): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2115): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e31e3e8
,E/SQLiteDBG( 2115): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x659a2ec0
,I/LocationSettingsChecker( 2115): Removing dialog suppression flag for package com.test.thalitest
,W/dalvikvm( 2115): threadid=47: thread exiting with uncaught exception (group=0x416cce30)
,E/DriveAsyncService( 2115): disk I/O error (code 3850)
E/DriveAsyncService( 2115): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2115): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2115): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2115): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2115): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2115): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2115): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2115): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2115): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2115): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2115): 	at java.lang.Thread.run(Thread.java:864)
,E/AndroidRuntime( 2115): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2115): Process: com.google.android.gms, PID: 2115
E/AndroidRuntime( 2115): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2115): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2115): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2115): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2115): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2115): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2115): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2115): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2115): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2115): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2115): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2115): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2115): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2115): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms
,E/SQLiteDatabase( 2115): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2115): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2115): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2115): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2115): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2115): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2115): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 2115): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2115): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2115): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2115): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2115): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2115): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2115): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2115): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2115): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2115): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2115): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2115): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2115): killProcess, pid=2115
D/Process ( 2115): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,W/SQLiteOpenHelper( 2115): Opened metrics.db in read-only mode
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b8fbd0 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/ActivityManager(  905): Recipient 2115
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): handleWLDeath(43e66ed0): PARTIAL_WAKE_LOCK  Icing 0x1
,I/ActivityManager(  905): Process com.google.android.gms (pid 2115) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10997ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10997ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10996ms
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10989ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10989ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20988ms
,E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fe8008
,W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x416cce30)
,E/AndroidRuntime( 1361): FATAL EXCEPTION: main
E/AndroidRuntime( 1361): Process: com.google.process.gapps, PID: 1361
E/AndroidRuntime( 1361): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1361): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1361): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1361): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1361): 	... 10 more
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,D/Process ( 1361): killProcess, pid=1361
,D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5152 uid=10098 gids={50098, 3003, 5012}

```
