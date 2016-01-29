#### Test 56818254e6f5c3b_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1485): handler message = 4011
E/HtcModeClient( 1485): Check connection and retry 12 times.
W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/cutils-trace( 4375): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4375): ====startRecUseTime====
D/htc.customization.log.level( 4375):  is 
W/CustomizationLogLevel( 4375): Level value is invalid, use default level 2
D/CustomizationManager( 4375):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4375): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4375): Parsing tag category name = system
I/CustomizationCIDLoader( 4375): Parsing tag category name = application
I/CustomizationCIDLoader( 4375): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4375): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4375): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4375): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4375): Parsing tag category name = Settings
D/CustomizationManager( 4375):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4375):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4375): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4375): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4375): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4375): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4375
D/PMS     (  906): acquireHCC(426c0590): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4264aff0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62c39850 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1117676264
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42172768
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
D/PMS     (  906): acquireWL(42502ab0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4386 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4386): Copying FileAsset 0x5c70f420 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4386): Binding Chromium to main looper Looper (main, tid 1) {42026150}
I/LibraryLoader( 4386): Expected native library version number "",actual native library version number ""
I/chromium( 4386): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4386): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(4360cb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4279df40:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4386): 1107542184: getState(). Returning 12
D/PMS     (  906): acquireWL(434fea48): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): releaseWL(434fea48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4386): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4386): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4386): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4386): Local Branch: 
I/Adreno-EGL( 4386): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4386): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4386):                  aa63bbd948f41d15fc72f585e
W/chromium( 4386): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4386): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4386): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4386): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4386): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4386): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4386): CordovaWebView is running on device made by: HTC
,W/AwContents( 4386): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,W/ResourceType( 4386): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4386): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4206d758, mServedView=org.apache.cordova.engine.SystemWebView{420333c0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4386
,W/AwContents( 4386): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +274ms
,D/PMS     (  906): releaseWL(42502ab0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4386): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4386): JniHelper::setJavaVM(0x41be5010), pthread_self() = 1662188352
,I/chromium( 4386): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.232MB for 323830-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.438MB for 485740-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.841MB for 728606-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 12.438MB for 1092904-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 13.305MB for 1639352-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 14.716MB for 2459024-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 15.396MB for 2288418-byte allocation
,W/jxcore-log( 4386): Initializing JXcore engine
,W/jxcore-log( 4386): JXcore engine is ready
,W/jxcore-log( 4386): Starting JXcore engine
,W/jxcore-log( 4386): Platform android
W/jxcore-log( 4386): 
,W/jxcore-log( 4386): Process ARCH arm
W/jxcore-log( 4386): 
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(426c0590): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(4264aff0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:73, mTXpacketCount:70, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  906): mEventCount = 900
,I/jxcore-log( 4386): JXcore Cordova bridge is ready!
I/jxcore-log( 4386): 
,W/jxcore-log( 4386): JXcore engine is started
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4386): Toggling radios to true
I/jxcore-log( 4386): 
,D/BluetoothAdapter( 4386): enable(): BT is already enabled..!
,D/WifiManager( 4386): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1349
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
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
D/WifiManager( 4386): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,D/WifiManager( 4386): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): TDLS: Tear down peers
,I/wpa_supplicant( 1168): wpa_driver_nl80211_disconnect(reason_code=3),
,I/jxcore-log( 4386): Radios toggled
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): My device name is: HTC-HTC Desire 820,
I/jxcore-log( 4386): 
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4386, uid=10189
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1168): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1168): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1168): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8993bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1168): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1168): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1168): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wp,a_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1168): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): interfaceLinkStateChanged wlan0, false,
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  906): acquireWL(4315e9e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): Fast associate: Old scan results
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19047 mDataStallAlarmIntent=PendingIntent{428da640: PendingIntentRecord{422529c8 android broadcastIntent}}
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1168): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906):    returned true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
,D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): acquireWL(43171300): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1406 10028 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/libc    (  366): [NET] entry_id:5   entry:0xb79abf78  removed 
D/libc    (  366): [NET] entry_id:4   entry:0xb79affd8  removed 
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  366): [NET] entry_id:2   entry:0xb79b0108  removed 
D/libc    (  366): [NET] entry_id:6   entry:0xb79ac150  removed 
D/libc    (  366): [NET] entry_id:3   entry:0xb79b02e0  removed 
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  366): [NET] entry_id:1   entry:0xb79b0410  removed 
,D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/PMS     (  906): acquireWL(43176f38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1406 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43177cd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1406/10028)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1168): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(43171300): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(43176f38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): releaseWL(43177cd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(4360cb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/NetworkMonitor( 3854): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(43194690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1862/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3854/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2745/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4440 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(43194690): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4440): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4440): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4440): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4440): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4440): Preparing secondary program dexes.
V/DexLibLoader( 4440): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4440): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4440): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4440): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4440): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4440): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4440): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4440): Dex already copied
D/OdexVerifier( 4440): Odex verification is skipped.
,V/DexLibLoader( 4440): Creating class loader
,V/DexLibLoader( 4440): Finished creating class loader
V/DexLibLoader( 4440): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4440): Dex already copied
D/OdexVerifier( 4440): Odex verification is skipped.
,V/DexLibLoader( 4440): Creating class loader,
V/DexLibLoader( 4440): Finished creating class loader
,V/DexLibLoader( 4440): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4440): Dex already copied
,D/OdexVerifier( 4440): Odex verification is skipped.
,V/DexLibLoader( 4440): Creating class loader
,V/DexLibLoader( 4440): Finished creating class loader
V/DexLibLoader( 4440): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4440): Dex already copied
D/OdexVerifier( 4440): Odex verification is skipped.
,V/DexLibLoader( 4440): Creating class loader,
V/DexLibLoader( 4440): Finished creating class loader
,V/DexLibLoader( 4440): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4440): DexLibLoader.ensureDexLoaded took 20 ms
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1485): Don't start project servcice
,D/HtcModeClient( 1485): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1485): connectState: CONNECTION_READY = false
D/SilentMusic( 1485): call stop
D/HtcModeClient( 1485): close connection
,W/HtcModeClient( 1485): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1485): read the terminate packet, so break
,W/dalvikvm( 4440): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1168): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1168): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1168): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
D/wpa_supplicant( 1168): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1168): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1168): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1168): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1168): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1168): wpa_supplicant_pick_network+
I/wpa_supplicant( 1168): Selecting BSS from priority group 1
I/wpa_supplicant( 1168): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1168): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1168): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1168): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1168):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1168):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1168): Start print parameters
I/wpa_supplicant( 1168): wpa_s->wpa_state is 3
I/wpa_supplicant( 1168): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1168): isConcurrentMode() is 0
I/wpa_supplicant( 1168): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1168): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1168): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1168): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1168): wpa_s->reassociate is 1
I/wpa_supplicant( 1168): wpa_s->is_screen_on 1
I/wpa_supplicant( 1168): wpa_s->ifname wlan0
I/wpa_supplicant( 1168): End print parameters
I/wpa_supplicant( 1168): selected network = 1
D/wpa_supplicant( 1168): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb89954e8  current_ssid=0x0
D/wpa_supplicant( 1168): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1168): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1168): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1168): check if in concurrent case
,I/wpa_supplicant( 1168): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 1168): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1168): RSN: PMKSA cache search - network_ctx=0xb89954e8 try_opportunistic=0
D/wpa_supplicant( 1168): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1168): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1168): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1168): nl80211: Unsubscribe mgmt frames handle 0xb8994718 (mode change)
D/wpa_supplicant( 1168): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8994718
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb8994718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1168):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168):   * freq=2412
D/wpa_supplicant( 1168):   * Auth Type 0
D/wpa_supplicant( 1168):   * WPA Versions 0x2
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1168): nl80211: Connect request send successfully
,D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1168): reply (489) for get BSS: id=0
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1168): freq=5220
I/wpa_supplicant( 1168): level=-48
I/wpa_supplicant( 1168): tsf=0000000021030984
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG7005g
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=1
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-48
I/wpa_supplicant( 1168): tsf=0000000094241180
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG700
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=2
I/wpa_supplicant( 1168): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1168): freq=2452
I/wpa_supplicant( 1168): level=-83
I/wpa_supplicant( 1168): tsf=0000000094241185
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=Gonzos
I/wpa_supplicant( 1168): ====,
I/wpa_supplicant( 1168): id=3
I/wpa_supplicant( 1168): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-48
I/wpa_supplicant( 1168): tsf=0000000094241176
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1168): ssid=01ABC
I/wpa_supplicant( 1168): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 21030984, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 94241180, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2452, timestamp: 94241185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 94241176, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4440): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4440): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1168): nl80211: Connect event
D/wpa_supplicant( 1168): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1168): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1168): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1168): TDLS: Remove peers on association
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1168): EAPOL: enable timer tick
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1168): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1168): Get randomness: len=32 entropy=5
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
D/HTCRequest(  906): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb89949f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f6bb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1168):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1168): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1168): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1168): wlan0: Connect to SSID: NG700
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1168): set send_ind_to_ndc = 0
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1168): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1168): EAPOL authentication completed successfully
I/wpa_supplicant( 1168): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3786): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3786): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 1
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
,D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(4329bf40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4292a128 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4292a128 target=com.android.internal.util.StateMachine$SmHandler }
,E/FbInjectorInitializer( 4440): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4440): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4440): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4440): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3463
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3463:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  906): acquireWL(4306d950): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2858 10028 null
,D/PMS     (  906): acquireWL(42a798d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2858 10028 null
,D/PMS     (  906): releaseWL(4306d950): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
,D/GCM     ( 1406): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
,D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): releaseWL(42a798d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4469 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): Util - no network available!
,D/AutoSetting( 1385): service - onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
D/AutoSetting( 1385): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 429ff8e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1385): service - mHandler: cancel location update
D/AutoSetting( 1385): service -           changes count: 0
,I/ActivityManager(  906): Recipient 3463
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4440): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4440): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4469): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4469): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4469): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4469): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4440): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4485 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4469/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4469/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4469/10078)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4440): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4502 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4204
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 4204:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/dalvikvm( 4440): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4440): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4440): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4440): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4440): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4440): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4440): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4440): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4440): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4440): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4440): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4440): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4440): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4440): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4440): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4440): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 9.928MB for 39954-byte allocation
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4502): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4502): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 4502): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4502): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4502): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 10.004MB for 79892-byte allocation
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 4204
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 10.066MB for 84664-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4502/10151)
,V/WebViewChromiumFactoryProvider( 4502): Binding Chromium to main looper Looper (main, tid 1) {4202a380}
,I/LibraryLoader( 4502): Expected native library version number "",actual native library version number ""
,I/chromium( 4502): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4502): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43e04e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4502): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43e1f800): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): releaseWL(43e04e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4502): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4502): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4502): Local Branch: 
I/Adreno-EGL( 4502): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4502): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4502):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4502): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4502/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4502/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4067/10160)
,I/dalvikvm-heap( 4440): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/Process (  906): killProcessQuiet, pid=3836
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4067/10160)
I/ActivityManager(  906): Killing 3836:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
D/ConnectivityService(  906): getAllNetworkInfo called by com.test.thalitest (4386/10189)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/GCM     ( 1406): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4369d5d8 u0 ReceiverList{43696010 4440 com.facebook.katana/10026/u0 remote:436829b0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4369d5d8 u0 ReceiverList{43696010 4440 com.facebook.katana/10026/u0 remote:436829b0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43da1bf0 u0 ReceiverList{43da1b90 4440 com.facebook.katana/10026/u0 remote:43cd9860}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/PMS     (  906): acquireWL(43344c28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  906): releaseWL(43344c28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1168): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1168): EAPOL: disable timer tick
,D/GCoreFlp( 1505): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43f0a848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
I/ActivityManager(  906): Recipient 3836
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(43f0a848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4440): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4440): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(4329bf40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19049 delay=15s
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 3786): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
I/ActivityManager(  906): Waited long enough for: ServiceRecord{43dbf0f8 u0 com.htc.htclocationservice/.AutoSettingService}
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@4295a4e8
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
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
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(43cd7b90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4469/10078)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  906): acquireWL(43b06b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2858 10028 null
,I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
,I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  366): RTNETLINK answers: No such process,
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43cd7b90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(44390620): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2858 10028 null
,D/PMS     (  906): releaseWL(43b06b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
I/CheckinService( 2858): Preparing to send checkin request
I/EventLogService( 2858): Accumulating logs since 1454085640090
,I/GoogleHttpClient( 2858): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2858): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2858/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2858/10028)
,W/GLSUser ( 1406): GoogleAccountDataService.getToken()
,W/GLSActivity( 1406): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1406): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1406): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2858): awaiting user notification for token
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4216ec10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 6 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4575 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4575): install
,I/MultiDex( 4575): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4575): loading existing secondary dex files
,I/MultiDex( 4575): load found 1 secondary dex files
,I/MultiDex( 4575): install done
,I/ProviderInstaller( 4575): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1406): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4575/10028)
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4575): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4575): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4575):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4575): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4575): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4575):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4575): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4575): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4575): Local Branch: 
I/Adreno-EGL( 4575): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4575): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4575):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 2
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  906): releaseWL(4315e9e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/PMS     (  906): acquireWL(43122e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1505/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1862/1000)
D/PMS     (  906): releaseWL(43122e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3854/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4469/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1862): Checking Certificates
I/acms    ( 1862): Checking Developer Certificates
I/acms    ( 1862): Checking Application Certificates
I/acms    ( 1862): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1862): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1862): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1862): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1862): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1862): Updating next query delay: 75600000
I/mlserverapp( 1862): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1862): cancelACMSProgrammedChecks
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3854): type=WIFI subType= reason=null isConnected=true
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3889/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(428c6558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
D/PMS     (  906): releaseWL(428c6558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2745/10021)
,D/PMS     (  906): acquireWL(4296a938): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2858 10028 null
D/PMS     (  906): releaseWL(4296a938): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/GCM     ( 1406): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/libc    ( 1406): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1406): [NET] getaddrinfo-,err=8
D/libc    ( 1406): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1406): [NET] getaddrinfo-, 1
,D/libc    ( 1406): [NET] getaddrinfo_proxy+
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/PMS     (  906): acquireWL(42921ef8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1406 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =fc74 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
D/AutoSetting( 1385): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4469): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4469): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1385): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1385): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1385): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1385): service - handleMessage() setting current location null
D/AutoSetting( 1385): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1385): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4502/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1385/10053)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4067/10160)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4067/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1808/10178)
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/libc    (  366): [NET]res_nsend:resplen=79
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1406): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4067): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
D/ConnectivityService(  906): getAllNetworkInfo called by com.test.thalitest (4386/10189)
,D/libc    ( 1406): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1406): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/PMS     (  906): acquireWL(4290c370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1406 10028 null
D/PMS     (  906): releaseWL(4290c370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4575): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [6][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-49 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  906): acquireWL(42982248): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1406 10028 null
,D/GCM     ( 1406): Connected
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/PMS     (  906): releaseWL(42921ef8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1406/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4386): 
D/PMS     (  906): releaseWL(42982248): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42919fc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1406 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1406/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1406): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1406/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
D/PMS     (  906): acquireWL(429cd240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1406 10028 null
D/PMS     (  906): releaseWL(429cd240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(42919fc8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/CheckinTask( 2858): Sending checkin request (8963 bytes)
D/libc    ( 2858): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2858): [NET] getaddrinfo-,err=8
D/libc    ( 2858): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2858): [NET] getaddrinfo-, 1
,D/libc    ( 2858): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =15a8 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  366): [NET]res_nsend:resplen=84
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2858): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,W/fb4a(:<default>):UserScope( 4440): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4440): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 2858): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2858): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/PMS     (  906): acquireWL(42aeb380): PARTIAL_WAKE_LOCK  Icing 0x1 2858 10028 null
,D/PMS     (  906): releaseWL(42aeb380): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(428ae4b8): PARTIAL_WAKE_LOCK  Icing 0x1 2858 10028 null
,D/PMS     (  906): releaseWL(428ae4b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42ba3b30): PARTIAL_WAKE_LOCK  Icing 0x1 2858 10028 null
E/fb4a(:<default>):LocalFbBroadcastManager( 4440): Called registerBroadcastReceiver twice.
,D/PMS     (  906): releaseWL(42ba3b30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(4345e518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1406 10028 null
,D/PMS     (  906): releaseWL(4345e518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2858/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2858/10028)
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1406): GoogleAccountDataService.getToken()
,W/GLSActivity( 1406): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1406): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1406): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2858): awaiting user notification for token
D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/PMS     (  906): releaseWL(43e1f800): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42170828 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 2 12
,I/CheckinTask( 2858): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2858): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
,D/GCM     ( 1406): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): releaseWL(44390620): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/GCM     ( 1406): GCM config loaded
,E/ActivityThread( 2858): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@422c8cb0 that was originally bound here
E/ActivityThread( 2858): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@422c8cb0 that was originally bound here
E/ActivityThread( 2858): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2858): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2858): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2858): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2858): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2858): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2858): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2858): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2858): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2858): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2858): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2858): 	at bks.a(SourceFile:298)
E/ActivityThread( 2858): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2858): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2858): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2858): 	at java.lang.Thread.run(Thread.java:864)
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4386): 
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =e712 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=172
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4616 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(4362f098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{42037588: PendingIntentRecord{42038250 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454085688760, Int=60000
,D/PMS     (  906): releaseWL(4362f098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4616): SMSBackupAgentService started
,D/SMSBackup( 4616): Checking restore status
D/SMSBackup( 4616): Restore complete
,D/SMSBackup( 4616): cancelCheckAlarm
,D/SMSBackup( 4616): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=4242
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4242:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4242
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4502): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(42b65908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  906): acquireWL(42bc8bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1505 10028 null
,D/PMS     (  906): releaseWL(42b65908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(42bc8bb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1050
,D/Process (  906): killProcessQuiet, pid=4273
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4273:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4273
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:39, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4386): Test app app.js loaded
I/jxcore-log( 4386): 
,W/dalvikvm( 4386): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4386): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4386): BLE advertisement is supported
I/jxcore-log( 4386): 
,I/chromium( 4386): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4440/10026)
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@425622d8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@425622d8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425ab198
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42896600
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 373ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  906): Disable input method client, pid=4386
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0
W/ResourceType( 4386): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4386): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{420333c0 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43f2a240)
,D/NfcService( 1253): applyRouting -2
D/PMS     (  906): acquireWL(43d7b758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(43f0ce30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  906): releaseWL(43f0ce30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(43d7b758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  906): onScreenOn
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MtpService( 2745): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2745): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
I/HtcPowerSaver(  906): << updateStatus
,D/NfcService( 1253): applyRouting -2
,D/AutoSetting( 1385): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1385): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3786): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3786): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3786): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3786): Cust_ConnectToPC   : spcsc>false
D/PMS     (  906): acquireWL(43dee940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  906): releaseWL(43dee940): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/        ( 3786): Cust_ConnectToPC   : IPT>true
D/        ( 3786): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3786): hasRemovableStorageSlot: true
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/SmartNS_Utility( 3786): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3786): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19050 delay=15s
I/PSReceiver( 3786): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 3786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
I/SmartNS_PSService( 3786): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3786): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3786):  defaultType:0
,I/ClockThread( 1117): stop update clock
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): SET_SCREEN_ON:On
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): WifiActivity: 3
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
V/SRS_Proc(  373): ParamSet string: screen_state=on
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4641 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
,W/ContextImpl( 4641): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(42ac0ea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
,D/PMS     (  906): acquireWL(43da1f38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4641 1000 null
D/SmartSyncUtils( 4641): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1454085695980
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1454085695981
D/PMS     (  906): releaseWL(42ac0ea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425ab198
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425ab198, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42896600
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43767148): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43da1f38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19050 mDataStallAlarmIntent=PendingIntent{436e52c8: PendingIntentRecord{422529c8 android broadcastIntent}}
D/PMS     (  906): releaseWL(43767148): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,D/PMS     (  906): acquireWL(43f23748): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): SET_SCREEN_ON:Off
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1168): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4641): getMobilePolicyEnabled, result = true
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): releaseWL(43f23748): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
W/ContextImpl( 4641): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4641): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4641): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4641): isEpsOn(), nState = 0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42896600
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42896600, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42896600, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42896600
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429e75c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429e75c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/PhoneStatusBar( 1117): removeHeadsNotification.gc: 51
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(43f1f1a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
,D/PMS     (  906): releaseWL(43f1f1a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
D/AutoSetting( 1385): service - mHandler: cancel location update
D/AutoSetting( 1385): service -           changes count: 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42d8c420 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/AutoSetting( 1485): service - handleMessage() stop self
,D/AutoSetting( 1485): service - onDestroy() END
,D/AutoSetting( 1485): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4296
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4296:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4296
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3889
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3889:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3889
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/AutoSetting( 1385): service - mHandler: update timezone
,D/AutoSetting( 1485): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1485): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1485): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1485): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1485): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/DotMatrix( 1558): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1485): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1485): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1485): service - mHandler: update timezone
,D/AutoSetting( 1485): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1485): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1485): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1485): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42171a20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  906): acquireWL(43dd1a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4255b158: PendingIntentRecord{42849b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130981, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43dd1a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43dcba00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43dcba00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
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
,D/PMS     (  906): acquireWL(43cd9e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43cd9e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1385): service - handleMessage() stop self
,D/AutoSetting( 1385): service - onDestroy() END
,D/AutoSetting( 1385): service - handleMessage() quit looper
,I/ActivityManager(  906): Killing 4313:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4313
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4313
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(436b17b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{429f07d0: PendingIntentRecord{42b20258 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137132, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{429846e8: PendingIntentRecord{429f3160 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140590, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1406/10028)
,D/PMS     (  906): acquireWL(43674f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1406 10028 null
,D/PMS     (  906): releaseWL(43674f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(4360cb30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(436b17b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =40da +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=238
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44305fd8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(4360cb30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/AutoSetting( 1485): service - handleMessage() stop self
,D/AutoSetting( 1485): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4334
,I/ActivityManager(  906): Killing 4334:com.htc.calendar/u0a13 (adj 15): empty #17
D/AutoSetting( 1485): service - handleMessage() quit looper
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4334
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4203a3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4255b158: PendingIntentRecord{42849b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190981, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4203a3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42038d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42038d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428896a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4262e550: PendingIntentRecord{43b65570 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=215322, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4674 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{429d6548: PendingIntentRecord{42a13700 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454085800250, Int=10800000
,D/PMS     (  906): releaseWL(428896a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4674/10047)
,D/Process (  906): killProcessQuiet, pid=4260
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4260:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4260
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2858/10028)
,D/PMS     (  906): acquireWL(42b1ae80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{428395d8: PendingIntentRecord{43b65570 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226984, Int=0
,D/PMS     (  906): releaseWL(42b1ae80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42985e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4255b158: PendingIntentRecord{42849b98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250981, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42985e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4284b6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4284b6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425eb800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(425eb800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4386): --= Surplus to requirements =--
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): ****TEST TOOK:  ms ****
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4386): 
,E/cutils-trace( 4696): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4696): ====startRecUseTime====
D/htc.customization.log.level( 4696):  is 
,W/CustomizationLogLevel( 4696): Level value is invalid, use default level 2
,D/CustomizationManager( 4696):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4696): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4696): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4696): Parsing tag category name = system
,I/CustomizationCIDLoader( 4696): Parsing tag category name = application
I/CustomizationCIDLoader( 4696): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4696): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4696): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4696): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4696): Parsing tag category name = Settings
,D/CustomizationManager( 4696):  Read CID file spent 0.160 (s)
,D/CustomizationManager( 4696):  All configurations done spent 0.160 (s)
,W/HtcNativeFlag( 4696): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4696): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4696): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4696): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4696, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4386
,I/ActivityManager(  906): Killing 4386:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42822320 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x6c0c4d30 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4386 uid 10189
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  906): channel '430d3128 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '430d3128 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '430d3128 com.test.thalitest.MainActivity (s)'
I/WindowState(  906): WIN DEATH: Window{430d3128 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
,I/WindowManager(  906): WINDOW DIED Window{430d3128 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/dalvikvm-heap( 4067): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1505): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1862): Unregistering com.test.thalitest
,E/acms    ( 1862): Could not unregister removed application com.test.thalitest
D/PMS     (  906): acquireWL(43121668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1505 10028 null
D/PMS     (  906): releaseWL(43121668): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,D/VoicemailCleanupService( 1283): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
,D/PackageBroadcastService( 2858): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4712 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/MultiDex( 4712): install
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/MultiDex( 4712): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/MultiDex( 4712): loading existing secondary dex files
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4712): load found 1 secondary dex files
I/MultiDex( 4712): install done
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4728 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 2858): CP2 sync disabled
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2858, uid=10028, userID:0
,D/PMS     (  906): acquireWL(42afe470): PARTIAL_WAKE_LOCK  Icing 0x1 2858 10028 null
,I/Icing   ( 2858): doRemovePackageData com.test.thalitest
,D/PMS     (  906): releaseWL(42afe470): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4712): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/MultiDex( 4728): install
,I/MultiDex( 4728): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4728): loading existing secondary dex files
I/MultiDex( 4728): load found 1 secondary dex files
I/MultiDex( 4728): install done
,I/ProviderInstaller( 4728): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4348
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4348:com.android.settings:remote/1000 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1385): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1385): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2935): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  906): Recipient 4348
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4751 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteLog( 2935): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2935): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635983a0
,W/dalvikvm( 2935): threadid=16: thread exiting with uncaught exception (group=0x41bf6e30)
,E/AndroidRuntime( 2935): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2935): Process: com.google.android.googlequicksearchbox:search, PID: 2935
E/AndroidRuntime( 2935): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2935): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2935): 	at cid.d(PG:186)
E/AndroidRuntime( 2935): 	at clo.g(PG:594)
E/AndroidRuntime( 2935): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2935): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2935): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2935): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2935): 	at clr.tL(PG:827)
E/AndroidRuntime( 2935): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2935): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2935): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2935): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 2935): killProcess, pid=2935
,D/Process ( 2935): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  906): Can't write: system_app_crash
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
E/SQLiteDatabase( 4712): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4712): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4712): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4712): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4712): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4712): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4712): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4712): threadid=12: thread exiting with uncaught exception (group=0x41bf6e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4712): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4712): Process: com.google.android.gms.drive, PID: 4712
E/AndroidRuntime( 4712): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4712): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4712): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4712): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4712): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4712): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4712): 	at ctn.run(SourceFile:985)
I/ActivityManager(  906): Recipient 2935
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2935) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2935): Died!
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/Process ( 4712): killProcess, pid=4712
,D/Process ( 4712): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
,W/PackageManager(  906): Unable to load service info ResolveInfo{433230b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4712
,I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4712) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10826ms
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4751): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4751): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4751): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4751): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4751): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4751): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4751): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4751): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4751): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4751): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4751): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4751): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4751): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4751): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4751): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4751): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4751): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4751): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4751): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829),
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4751): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4751): 	,at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4751): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4751): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4751): 	,at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4751): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4751): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4751): ,	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4751): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4751): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4751): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4751): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4751): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4751): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4751): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4751): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4751): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4751): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4751): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4751): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4751): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/SQLiteDatabase( 4751): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4751): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4751): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4751): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4751): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4751): threadid=11: thread exiting with uncaught exception (group=0x41bf6e30)
E/AndroidRuntime( 4751): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4751): Process: com.google.android.apps.docs, PID: 4751
E/AndroidRuntime( 4751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4751): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4751): 	,at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4751): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4751): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4751): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4751): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
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
,D/Process ( 4751): killProcess, pid=4751
,D/Process ( 4751): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4769 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 4751
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process (  906): killProcessQuiet, pid=4090
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4090:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4751) has died.
,I/ActivityManager(  906): Recipient 4090
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4769): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4769): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4769): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4769): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4769): threadid=10: thread exiting with uncaught exception (group=0x41bf6e30)
E/AndroidRuntime( 4769): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4769): Process: com.android.keychain, PID: 4769
E/AndroidRuntime( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4769): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4769): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4769): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4782 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4769): killProcess, pid=4769
,D/Process ( 4769): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454085867747.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 4769
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.android.keychain (pid 4769) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10430ms
,D/AppTag  ( 4782): getInstance(Context context)
,D/AppTag  ( 4782): getInstance(Context context)
,D/AppTag  ( 4782): onCreate()
,D/PMS     (  906): acquireWL(42b4c200): PARTIAL_WAKE_LOCK  AsyncService 0x1 4067 10160 null
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4800 uid=10098 gids={50098, 3003, 5012}
,I/dalvikvm-heap( 4067): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(42b4c200): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/DeviceManagement( 4800): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4800 dbg=false s=true
,I/DeviceManagement( 4800): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4800): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4800): WorkflowService: Starting workflow service
I/DeviceManagement( 4800): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@420581a8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4800): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4800): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4800): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4800): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4814 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4800): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@420b9dd0 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/DeviceManagement( 4800): SessionStateController: Checking invariants...
,D/Documents( 4814): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4814): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4814): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4814): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4814): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4814): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4814): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4814): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4814): threadid=1: thread exiting with uncaught exception (group=0x41bf6e30)
E/AndroidRuntime( 4814): FATAL EXCEPTION: main
E/AndroidRuntime( 4814): Process: com.android.documentsui, PID: 4814
E/AndroidRuntime( 4814): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4814): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4814): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4814): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4814): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4814): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4814): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4814): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4814): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4814): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4814): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4814): 	... 10 more
,I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4828 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  906): killProcessQuiet, pid=3854
,I/ActivityManager(  906): Killing 3854:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  906): App crashed! Process: com.android.documentsui
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1406): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process (  906): killProcessQuiet, pid=4469
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454085868090.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Killing 4469:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/Process ( 4814): killProcess, pid=4814
,D/Process ( 4814): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Recipient 4469
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 4814
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.android.documentsui (pid 4814) has died.
,D/GCM     ( 1406): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/SQLiteDatabase( 4800): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4800): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4800): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4800): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4800): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4800): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4800): 	at java.lang.Thread.run(Thread.java:864)
D/ExternalStorage( 4828): After updating volumes, found 1 active roots
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/DeviceManagement( 4800): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4800): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4800): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4800): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4800): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4800): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4800): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4800): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4800): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Resuming delayed broadcast
W/DeviceManagement( 4800): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@420581a8]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4800): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4800): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4800): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4800): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4800): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4800): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4844 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/DeviceManagement( 4800): WorkflowService: Stopping workflow service
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3854
D/MediaRouterService(  906): Client com.google.android.music (pid 3854): Died!
,I/ActivityManager(  906): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService: pid=4858 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,E/SQLiteDatabase( 4844): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4844): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4844): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4844): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4844): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4844): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4844): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4844): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4844): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4844): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4844): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4844): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4844): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4844): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4844): Opened MyDB.db in read-only mode

```
