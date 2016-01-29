#### Test 57531243c766d4e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1464): handler message = 4011
E/HtcModeClient( 1464): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1464): Don't start project servcice
D/HtcModeClient( 1464): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1464): connectState: CONNECTION_READY = false
D/SilentMusic( 1464): call stop
D/HtcModeClient( 1464): close connection
W/HtcModeClient( 1464): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1464): read the terminate packet, so break
,E/cutils-trace( 4403): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4403): ====startRecUseTime====
D/htc.customization.log.level( 4403):  is 
W/CustomizationLogLevel( 4403): Level value is invalid, use default level 2
D/CustomizationManager( 4403):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4403): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4403): Parsing tag category name = system
I/CustomizationCIDLoader( 4403): Parsing tag category name = application
I/CustomizationCIDLoader( 4403): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4403): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4403): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4403): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4403): Parsing tag category name = Settings
D/CustomizationManager( 4403):  Read CID file spent 0.102 (s)
D/CustomizationManager( 4403):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4403): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4403): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4403
D/PMS     (  904): acquireHCC(44452020): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(42d23fa0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6dc3aec8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1140175208
D/PMS     (  904): acquireWL(44456d50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42442e58
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4414 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4414): Copying FileAsset 0x5c80f428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4414): Binding Chromium to main looper Looper (main, tid 1) {42288548}
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
I/chromium( 4414): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4414): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(42cdec08): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  904): acquireWL(43497680): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d40348:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4414): 1110040448: getState(). Returning 12
D/PMS     (  904): releaseWL(43497680): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4414): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4414): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4414): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4414): Local Branch: 
I/Adreno-EGL( 4414): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4414): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4414):                  aa63bbd948f41d15fc72f585e
W/chromium( 4414): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4414): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4414): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4414): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4414): CordovaWebView is running on device made by: HTC
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +278ms
W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422cf630, mServedView=org.apache.cordova.engine.SystemWebView{42295298 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  904): Disable input method client, pid=1273
I/InputMethodManagerService(  904): Enable input method client, pid=4414
D/PMS     (  904): releaseWL(44456d50): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4414): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4414): JniHelper::setJavaVM(0x41e45010), pthread_self() = 1662003376
,I/chromium( 4414): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4353a4d0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.233MB for 323830-byte allocation
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.498MB for 485740-byte allocation
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.863MB for 728606-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.438MB for 1092904-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 13.346MB for 1639352-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 14.716MB for 2459024-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 15.410MB for 2288606-byte allocation
,W/jxcore-log( 4414): Initializing JXcore engine
,W/jxcore-log( 4414): JXcore engine is ready
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
,D/PMS     (  904): releaseHCC(44452020): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,D/PMS     (  904): releaseHCC(42d23fa0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4414): Starting JXcore engine
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
,W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,I/jxcore-log( 4414): Toggling radios to true
I/jxcore-log( 4414): 
,D/BluetoothAdapter( 4414): enable(): BT is already enabled..!
,D/WifiManager( 4414): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1430
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
,D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=4414, uid=10189
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4414): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiManager( 4414): reconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): TDLS: Tear down peers
I/wpa_supplicant( 1174): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4414): Radios toggled
I/jxcore-log( 4414): 
I/jxcore-log( 4414): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4414): 
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1174): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1174): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1174): TDLS: Remove peers on disassociation
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb76c5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1174):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1174): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1174): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1174): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1174): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1174): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1174): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1174): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1174): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1174): nl80211: Event message available
D/wpa_supplicant( 1174): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1174): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  904):    returned true
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  904): release()
,D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
,D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 0
I/wpa_supplicant( 1174): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/PMS     (  904): acquireWL(43a80b40): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/WifiP2pService(  904): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): Fast associate: Old scan results
I/wpa_supplicant( 1174): wpa_supplicant_scan enter
I/wpa_supplicant( 1174): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1174): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1174): wpa_supplicant_trigger_scan +
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1174): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1174): nl80211: Event message available
D/wpa_supplicant( 1174): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): Enter handleNetworkDisconnect
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19805 mDataStallAlarmIntent=PendingIntent{42d7b9f8: PendingIntentRecord{42cdfb68 android broadcastIntent}}
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 0
I/wpa_supplicant( 1174): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
,D/WISPrService( 3789): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
,D/UsbnetStateTracker(  904): isAvailable+-
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/WifiService(  904): New client listening to asynchronous messages
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] entry_id:5   entry:0xb8b71270  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb8b713f8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8b71190  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8b714c0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8b71a00  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8b71588  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8b6c8b0  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb8b712f8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/PMS     (  904): acquireWL(4394a6f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1404 10028 null
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
,D/WISPrService( 3789): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3789): >>>>>WISPrService start isConnected = false<<<<<
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  904): acquireWL(43b17cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): releaseWL(43b17cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  904): acquireWL(439dab78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3789): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1404/10028)
D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  904): releaseWL(4394a6f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  904): releaseWL(439dab78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,D/PMS     (  904): releaseWL(42cdec08): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  904): NoActiveNetworkState
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1516/10028)
D/PMS     (  904): acquireWL(434a2ba0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1864/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4290): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4290/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4231/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4231/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2723/10021)
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4467 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/PMS     (  904): releaseWL(434a2ba0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4467): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4467): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4467): Preparing secondary program dexes.
V/DexLibLoader( 4467): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4467): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4467): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped.
,V/DexLibLoader( 4467): Creating class loader,
V/DexLibLoader( 4467): Finished creating class loader,
V/DexLibLoader( 4467): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
,V/DexLibLoader( 4467): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped.
,V/DexLibLoader( 4467): Creating class loader,
V/DexLibLoader( 4467): Finished creating class loader
,V/DexLibLoader( 4467): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4467): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4467): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1174): nl80211: Event message available
D/wpa_supplicant( 1174): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1174): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1174): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1174): nl80211: Survey data missing
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1174): Sorted scan results
I/wpa_supplicant( 1174): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1174): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1174): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1174): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-80
D/wpa_supplicant( 1174): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1174): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1174): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1174): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1174): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1174): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1174): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1174): wpa_supplicant_pick_network+
I/wpa_supplicant( 1174): Selecting BSS from priority group 1
I/wpa_supplicant( 1174): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1174): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1174): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1174): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1174):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1174):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 1174): Start print parameters
I/wpa_supplicant( 1174): wpa_s->wpa_state is 3
I/wpa_supplicant( 1174): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1174): isConcurrentMode() is 0
I/wpa_supplicant( 1174): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1174): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1174): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1174): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1174): wpa_s->reassociate is 1
I/wpa_supplicant( 1174): wpa_s->is_screen_on 1
I/wpa_supplicant( 1174): wpa_s->ifname wlan0
I/wpa_supplicant( 1174): End print parameters
I/wpa_supplicant( 1174): selected network = 1
D/wpa_supplicant( 1174): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb76c74e8  current_ssid=0x0
D/wpa_supplicant( 1174): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1174): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1174): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1174): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1174): check if in concurrent case
,I/wpa_supplicant( 1174): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1174): wpa_supplicant_associate, 1777,
D/wpa_supplicant( 1174): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1174): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1174): RSN: PMKSA cache search - network_ctx=0xb76c74e8 try_opportunistic=0
D/wpa_supplicant( 1174): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1174): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1174): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 1174): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1174): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1174): nl80211: Unsubscribe mgmt frames handle 0xb76c6718 (mode change)
D/wpa_supplicant( 1174): nl80211: Subscribe to mgmt frames with non-AP handle 0xb76c6718
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1174): nl80211: Register frame type=0xd0 nl_handle=0xb76c6718
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1174): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1174):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1174):   * freq=2412
D/wpa_supplicant( 1174):   * Auth Type 0
D/wpa_supplicant( 1174):   * WPA Versions 0x2
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1174): nl80211: Connect request send successfully
D/wpa_supplicant( 1174): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1174): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1174): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1174): reply (489) for get BSS: id=0
I/wpa_supplicant( 1174): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1174): freq=5220
I/wpa_supplicant( 1174): level=-48
I/wpa_supplicant( 1174): tsf=0000000099701119
I/wpa_supplicant( 1174): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1174): ssid=NG7005g
I/wpa_supplicant( 1174): ====
I/wpa_supplicant( 1174): id=1
,I/wpa_supplicant( 1174): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1174): freq=2412
I/wpa_supplicant( 1174): level=-48
I/wpa_supplicant( 1174): tsf=0000000099701136
I/wpa_supplicant( 1174): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1174): ssid=NG700
I/wpa_supplicant( 1174): ====
I/wpa_supplicant( 1174): id=2
I/wpa_supplicant( 1174): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1174): freq=2412
I/wpa_supplicant( 1174): level=-48
I/wpa_supplicant( 1174): tsf=0000000099701131
I/wpa_supplicant( 1174): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1174): ssid=01ABC
I/wpa_supplicant( 1174): ====
I/wpa_supplicant( 1174): id=3
I/wpa_supplicant( 1174): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1174): freq=2452
I/wpa_supplicant( 1174): level=-80
I/wpa_supplicant( 1174): tsf=0000000099701140
I/wpa_supplicant( 1174): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1174): ssid=Gonzos
I/wpa_supplicant( 1174): ####
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 99701119, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 99701136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 99701131, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2452, timestamp: 99701140, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  904): add 4 to mScanResults
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/BatSI   (  904): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/wpa_supplicant( 1174): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1174): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1174): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1174): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1174): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1174): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1174): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1174): nl80211: Event message available
D/wpa_supplicant( 1174): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1174): nl80211: Connect event
D/wpa_supplicant( 1174): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1174): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1174): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1174): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1174): Add randomness: count=9 entropy=4
I/wpa_supplicant( 1174): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1174): TDLS: Remove peers on association
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1174): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1174): EAPOL: enable timer tick
D/wpa_supplicant( 1174): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1174): htc_wext_set_keepalive +
I/wpa_supplicant( 1174): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1174): getPrivFuncNum +	
I/wpa_supplicant( 1174): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1174): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1174): Get randomness: len=32 entropy=5
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1174): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb76c69f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1174):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1174): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f30b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1174):    broadcast key
D/WifiStateMachine(  904): This record is existed, only update it...
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1174): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1174): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1174): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1174): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1174): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1174): set send_ind_to_ndc = 0
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1174): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1174): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1174): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1174): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1174): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1174): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1174): EAPOL authentication completed successfully
I/wpa_supplicant( 1174): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1174): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1174): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/wpa_supplicant( 1174): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3789): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3789): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1174): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(4230b538): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42bd8290 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42bd8290 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4480 uid=10077 gids={50077}
D/PMS     (  904): acquireWL(428562c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
V/AlarmManager(  904): sending alarm PendingIntent{42d9b7d8: PendingIntentRecord{42e1ca30 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454090230736, Int=60000
,D/PMS     (  904): releaseWL(428562c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,W/dalvikvm( 4467): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/SMSBackup( 4480): SMSBackupAgentService started
,D/SMSBackup( 4480): Checking restore status
D/SMSBackup( 4480): Restore complete
,D/SMSBackup( 4480): cancelCheckAlarm
,D/SMSBackup( 4480): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3217
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3217:com.android.defcontainer/u0a19 (adj 15): empty #17
,E/FbInjectorInitializer( 4467): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/ActivityManager(  904): Recipient 3217
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):StaticBindingVerifier( 4467): Verify
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=3603
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3603:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  904): acquireWL(42d3c760): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2835 10028 null
,D/PMS     (  904): acquireWL(42caeca8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2835 10028 null
,D/PMS     (  904): releaseWL(42d3c760): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/PMS     (  904): releaseWL(42caeca8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1404): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/AutoSetting( 1384): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  904): Recipient 3603
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4510 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1384/10053)
,D/AutoSetting( 1384): Util - no network available!
,D/AutoSetting( 1384): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1384): service - mHandler: cancel location update
,D/AutoSetting( 1384): service -           changes count: 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1384/10053)
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4467): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4510): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4510): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4524 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4201
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4201:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  904): Recipient 4201
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4467): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4467): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4467): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4467): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/Process (  904): killProcessQuiet, pid=4231
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4541 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 4231:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4231
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.903MB for 39954-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.979MB for 79892-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4541): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.049MB for 84664-byte allocation
,D/wpa_supplicant( 1174): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1174): EAPOL: disable timer tick
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,V/WebViewChromiumFactoryProvider( 4541): Binding Chromium to main looper Looper (main, tid 1) {4228d378}
,I/LibraryLoader( 4541): Expected native library version number "",actual native library version number ""
,I/chromium( 4541): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4541): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(42a3ba20): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  904): acquireWL(42d4b6b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4541): BLUETOOTH permission is missing!
,D/PMS     (  904): releaseWL(42d4b6b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.273MB for 75760-byte allocation
,I/Adreno-EGL( 4541): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4541): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4541): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4541): Local Branch: 
I/Adreno-EGL( 4541): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4541): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4541):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d1a610 u0 ReceiverList{42cf5f40 4467 com.facebook.katana/10026/u0 remote:42a3ee20}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d1a610 u0 ReceiverList{42cf5f40 4467 com.facebook.katana/10026/u0 remote:42a3ee20}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43cf16e8 u0 ReceiverList{43bb21d8 4467 com.facebook.katana/10026/u0 remote:42e1e448}}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,I/NSApplication( 4541): Starting up...
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,D/PMS     (  904): acquireWL(42e5c740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1516 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
,D/PMS     (  904): releaseWL(42e5c740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
,D/GCoreFlp( 1516): Unknown pending intent to remove.
D/PMS     (  904): acquireWL(42c79008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1516 10028 null
,D/Process (  904): killProcessQuiet, pid=4254
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  904): releaseWL(42c79008): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  904): Killing 4254:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (4414/10189)
,I/ActivityManager(  904): Recipient 4254
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/GCM     ( 1404): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1174): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  904): releaseWL(4230b538): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): gateway: /192.168.1.1
D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1174): WiFi gateway: 0x101a8c0
,D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19807 delay=15s
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  904): WAN detection
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WISPrService( 3789): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@42bb71a0
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  904): acquireWL(43e823d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  904): acquireWL(440482c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2835 10028 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [1][0][0]
D/PMS     (  904): acquireWL(43289388): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2835 10028 null
D/PMS     (  904): releaseWL(43e823d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  904): releaseWL(440482c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/CheckinService( 2835): Preparing to send checkin request
,I/EventLogService( 2835): Accumulating logs since 1454090181552
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2835): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2835): Using GMS GoogleHttpClient
,D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2835/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2835/10028)
,W/GLSUser ( 1404): GoogleAccountDataService.getToken()
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1404): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2835): awaiting user notification for token
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{422afbc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 6 2 12
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4616 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4616): install
,I/MultiDex( 4616): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4616): loading existing secondary dex files
,I/MultiDex( 4616): load found 1 secondary dex files
,I/MultiDex( 4616): install done
,I/ProviderInstaller( 4616): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1404): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4616/10028)
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1114): WifiActivity: 2
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  904): releaseWL(43a80b40): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/Tethering(  904): Found interface wlan0
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1516/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1864/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4290/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,I/acms    ( 1864): Checking Certificates
I/acms    ( 1864): Checking Developer Certificates
,I/acms    ( 1864): Checking Application Certificates
I/acms    ( 1864): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1864): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1864): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
,I/acms    ( 1864): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1864): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
I/acms    ( 1864): Updating next query delay: 75600000
I/mlserverapp( 1864): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1864): cancelACMSProgrammedChecks
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4290): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [1][0][0]
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(436146b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3875/10051)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(436daf20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(436daf20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  904): releaseWL(436146b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2723/10021)
,D/PMS     (  904): acquireWL(4428dbd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2835 10028 null
,D/PMS     (  904): releaseWL(4428dbd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1404): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/libc    ( 1404): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1404): [NET] getaddrinfo-,err=8
D/libc    ( 1404): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1404): [NET] getaddrinfo-, 1
,D/libc    ( 1404): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e9a3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): acquireWL(42e5f350): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1404 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/AutoSetting( 1384): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1384/10053)
,D/AutoSetting( 1384): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1384): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1384): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1384): service - onStartCommand() REMOVE current location bundle
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4541/10151)
D/AutoSetting( 1384): service - handleMessage() setting current location null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1384): Util - check NLP state, Allowned:false, Enabled:false
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1384/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4054/10160)
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1384): service - onStartCommand() check timezone in 30000
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 141
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1404): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1801/10178)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (4414/10189)
,I/dalvikvm-heap( 4054): Grow heap (frag case) to 13.515MB for 1821008-byte allocation
,W/Settings( 4616): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    ( 1404): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1404): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): acquireWL(444b4078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
D/PMS     (  904): releaseWL(444b4078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2835): Sending checkin request (8970 bytes)
D/libc    ( 2835): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2835): [NET] getaddrinfo-,err=8
D/libc    ( 2835): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2835): [NET] getaddrinfo-, 1
,D/libc    ( 2835): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =939b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=14 [7][1][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  904): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 56
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2835): [NET] getaddrinfo_proxy-, success
,D/GCM     ( 1404): Connected
D/PMS     (  904): acquireWL(438f16c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1404 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): releaseWL(42e5f350): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1404/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): releaseWL(438f16c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(44030610): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1404 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1404/10028)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1404): Message class mpf
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1404/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): acquireWL(43f707d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
D/PMS     (  904): releaseWL(44030610): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): releaseWL(43f707d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 2835): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2835): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4414): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4414): 
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=5 [18][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4467): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  904): acquireWL(43516198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
,D/PMS     (  904): releaseWL(43516198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2835/10028)
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2835/10028)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1404): GoogleAccountDataService.getToken()
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1404): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2835): awaiting user notification for token
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{42442850 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 6 2 12
,I/CheckinTask( 2835): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2835): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/GCM     ( 1404): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  904): releaseWL(43289388): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2835): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4231cf20 that was originally bound here
E/ActivityThread( 2835): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4231cf20 that was originally bound here
E/ActivityThread( 2835): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2835): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2835): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2835): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2835): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2835): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2835): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2835): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2835): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2835): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2835): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2835): 	at bks.a(SourceFile:298)
E/ActivityThread( 2835): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2835): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2835): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2835): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1404): GCM config loaded
,I/jxcore-log( 4414): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4414): 
,D/PMS     (  904): releaseWL(42a3ba20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4414): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4414): 
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bf48 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/23.59.123.86,
,I/GAV2    ( 4541): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(43c4c950): PARTIAL_WAKE_LOCK  Icing 0x1 2835 10028 null
,D/PMS     (  904): acquireWL(42dada50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1516 10028 null
,D/PMS     (  904): acquireWL(435384b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1516 10028 null
,D/PMS     (  904): releaseWL(42dada50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  904): releaseWL(435384b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  904): releaseWL(43c4c950): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(44040af0): PARTIAL_WAKE_LOCK  Icing 0x1 2835 10028 null
,D/PMS     (  904): releaseWL(44040af0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(43c583b8): PARTIAL_WAKE_LOCK  Icing 0x1 2835 10028 null
,D/PMS     (  904): releaseWL(43c583b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42904e48
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42904e48, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42aff4e8
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@4227bf60
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
D/WIFI_ICON( 1114): WifiActivity: 2
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  904): mWirelessDisplayManager is null
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 375ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=4414
,D/PMS     (  904): acquireWL(43c9ce60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42295298 VFEDH.C. .F...... 0,0-720,1134 #64}
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4348a618)
D/PMS     (  904): releaseWL(43c9ce60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  904): wakingUp
D/PMS     (  904): acquireWL(4456df80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(4456df80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMN     (  904): onScreenOn
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
D/MtpService( 2723): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2723): [MTP][onReceive]-
,D/AutoSetting( 1384): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): acquireWL(4347c8f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  904): releaseWL(4347c8f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19808 delay=15s
D/AutoSetting( 1384): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3789): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3789): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3789): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3789): Cust_ConnectToPC   : spcsc>false
D/        ( 3789): Cust_ConnectToPC   : IPT>true
D/        ( 3789): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
E/SmartNS_Utility( 3789): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/SmartNS_Utility( 3789): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3789): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): SET_SCREEN_ON:On
I/wpa_supplicant( 1174): htc_wext_set_keepalive +
I/wpa_supplicant( 1174): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1174): getPrivFuncNum +	
I/wpa_supplicant( 1174): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/PSReceiver( 3789): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
I/SmartNS_PSService( 3789): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3789):  defaultType:0
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:40, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
D/WifiStateMachine(  904): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ClockThread( 1114): stop update clock
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  904): updateScreenOn: false
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4664 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOn: 1454090237990
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOn: 1454090237991
D/PMS     (  904): acquireWL(43ea3dd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1516 10028 null
D/PMS     (  904): releaseWL(43ea3dd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 4664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42aff4e8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42aff4e8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@4227bf60
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(44304db8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4664 1000 null
,D/SmartSyncUtils( 4664): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(43ef16a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/PMS     (  904): releaseWL(44304db8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  904): releaseWL(43ef16a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19808 mDataStallAlarmIntent=PendingIntent{42ad6420: PendingIntentRecord{43495b60 android broadcastIntent}}
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): SET_SCREEN_ON:Off
I/wpa_supplicant( 1174): htc_wext_set_keepalive +
I/wpa_supplicant( 1174): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1174): getPrivFuncNum +	
I/wpa_supplicant( 1174): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1174): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1174): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1174): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1174): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904):    returned true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,D/PMS     (  904): acquireWL(436d9738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  904): updateScreenOn: false
,D/SmartSyncUtils( 4664): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(436d9738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  904): Killing 4272:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=4272
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4272
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4664): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4664): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4664): isEpsOn(), nState = 0
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4227bf60
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4227bf60, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4227bf60, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4227bf60
D/WifiService(  904): New client listening to asynchronous messages
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cc8df8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42cc8df8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] getTotalRam: 1873 Mb
D/AutoSetting( 1384): service - mHandler: cancel location update
,D/AutoSetting( 1384): service -           changes count: 0
D/PMS     (  904): acquireWL(4360c138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1516 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOff
D/PMS     (  904): releaseWL(4360c138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/Process (  904): killProcessQuiet, pid=4218
,I/ActivityManager(  904): Killing 4218:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4218
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4414): Test app app.js loaded
I/jxcore-log( 4414): 
,W/dalvikvm( 4414): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4414): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4414): BLE advertisement is supported
I/jxcore-log( 4414): 
,I/chromium( 4414): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/AutoSetting( 1464): service - handleMessage() stop self
,D/AutoSetting( 1464): service - onDestroy() END
,D/AutoSetting( 1464): service - handleMessage() quit looper
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.931MB for 10276-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.940MB for 15410-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.952MB for 23110-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.969MB for 34660-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.998MB for 51986-byte allocation
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 11.057MB for 65468-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 11.064MB for 44204-byte allocation
,D/libc    ( 4467): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4467): [NET] getaddrinfo-,err=8
D/libc    ( 4467): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4467): [NET] getaddrinfo-, 1
,D/libc    ( 4467): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7f8a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4467): [NET] getaddrinfo_proxy-, success
,I/global  ( 4467): call createSocket() return a new socket.
D/libc    ( 4467): [NET] getaddrinfo+,hn 11(0x33312e31332e36),sn(),family 0,flags 4
,D/libc    ( 4467): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4467): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4467): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(44633340): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4467 10026 null,
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4467): I/O error closing connection
I/global  ( 4467): java.net.SocketException: Socket is closed
I/global  ( 4467): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4467): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4467): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4467): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4467): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4467): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4467): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4467): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4467): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4467): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4467): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4467): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4467): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4467): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4467): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4467): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4467): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4467): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4467): Removing a connection that never existed!
D/PMS     (  904): releaseWL(44633340): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/Process (  904): killProcessQuiet, pid=3875
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3875:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3875
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(444a6cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(444a6cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1384): service - mHandler: update timezone
,D/AutoSetting( 1464): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1464): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1464): service - onCreate()
,D/AutoSetting( 1464): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1464): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1554): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1464): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1464): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1464): service - mHandler: update timezone
,D/AutoSetting( 1464): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1464): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1464): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1464): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1114): removeNotification.gc:61
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{4233f730 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 10 3 11
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1384): service - handleMessage() stop self
,D/AutoSetting( 1384): service - onDestroy() END
,D/AutoSetting( 1384): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4312
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4312:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4312
,D/WifiService(  904): Client connection lost with reason: 4
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(4429e6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{4280dfe8: PendingIntentRecord{42c6d600 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137326, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42c52970: PendingIntentRecord{42c59a08 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141305, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/PMS     (  904): acquireWL(44280ce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): acquireWL(44280b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
D/PMS     (  904): releaseWL(4429e6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): releaseWL(44280b50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cd01 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(44280ce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{443dbb98 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(42826568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42826568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1464): service - handleMessage() stop self
,D/AutoSetting( 1464): service - onDestroy() END
,D/AutoSetting( 1464): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4337
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4337:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4337
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(4289da40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4289da40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(42960700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42960700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1),
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b71d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b71d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42626000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{429afc58: PendingIntentRecord{43e0f968 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=220901, Int=0
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4702 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{42d85c20: PendingIntentRecord{42dfa138 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454090341906, Int=10800000
,D/PMS     (  904): releaseWL(42626000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4702/10047)
,D/Process (  904): killProcessQuiet, pid=4359
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4359:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4359
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2835/10028)
,D/PMS     (  904): acquireWL(42b16cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{42e422e0: PendingIntentRecord{43e0f968 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227204, Int=0
,D/PMS     (  904): releaseWL(42b16cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  904): acquireWL(42844bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(42844bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42a18110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a18110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(42b9fb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b9fb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(42b90758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b90758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42cfb970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/PMS     (  904): releaseWL(42cfb970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42e523c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=329185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42e523c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42bd9540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/DotMatrix( 1554): [EventService] reorderNotification, total:1
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1586): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/HtcPowerSaver(  904): updateBatteryInfo
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): releaseWL(42bd9540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3789): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3789): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3789): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3789): Cust_ConnectToPC   : spcsc>false
,D/        ( 3789): Cust_ConnectToPC   : IPT>true
D/        ( 3789): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3789): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3789): Index of the first 1 = -1
W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3789): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3789): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3789): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3789): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1404): GoogleAccountDataService.getToken()
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1404): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1404): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1404): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1404): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1404): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1404): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1404): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1404): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1404): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1404): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{4263f550 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 3998): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3998): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3998): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3998): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3998): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3998): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3998): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3998): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 9 3 12
,D/libc    ( 3998): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3998): [NET] getaddrinfo-,err=8
D/libc    ( 3998): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3998): [NET] getaddrinfo-, 1
,D/libc    ( 3998): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e782 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299,
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3998): [NET] getaddrinfo_proxy-, success
I/global  ( 3998): call createSocket() return a new socket.
D/libc    ( 3998): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3998): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3998): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3998): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(43cb99c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43cb99c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(434a0630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(434a0630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42bda8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=389185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42bda8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(439480a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{4352bf28: PendingIntentRecord{443d54e8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=407004, Int=300000
,V/AlarmManager(  904): sending alarm PendingIntent{438cc940: PendingIntentRecord{42d49f88 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454090511825, Int=1800000
,D/PMS     (  904): acquireWL(42cf91c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2835 10028 null
,D/PMS     (  904): releaseWL(439480a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(43f91710): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2835 10028 null
,I/EventLogService( 2835): Aggregate from 1454090232433 (log), 1454088711768 (data)
D/PMS     (  904): releaseWL(42cf91c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  904): releaseWL(43f91710): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42cd7d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42cd7d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42cd9be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=449185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42cd9be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42d714b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42d714b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(4279b828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=509185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4279b828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(442dea58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(442dea58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42c3f1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=99
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(42c3f1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(442abee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=569185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(442abee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(438f3cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438f3cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  904): acquireWL(442f6448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=629184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(442f6448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(439dca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(439dca80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42d2c2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=689185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42d2c2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  904): killProcessQuiet, pid=4373
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4373:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4373
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(439f7120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(439f7120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4349ce10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1586): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderNotification, total:0
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4349ce10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,W/ContextImpl( 4664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/TetherSettings( 3789): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3789): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3789): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3789): Cust_ConnectToPC   : spcsc>false
D/        ( 3789): Cust_ConnectToPC   : IPT>true
,D/        ( 3789): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3789): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3789): Index of the first 1 = -1
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Settings( 3789): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 3789): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3789): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3789): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/PMS     (  904): acquireWL(439a7580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=749185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439a7580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(443b2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(443b2ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43212330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=809184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43212330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43c55a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c55a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(436ea6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=869184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(436ea6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43907538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43907538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43c50750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=929184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c50750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4304a6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{4352bf28: PendingIntentRecord{443d54e8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=707004, Int=300000
,V/AlarmManager(  904): sending alarm PendingIntent{42575fc8: PendingIntentRecord{42bc1958 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782914, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42941090: PendingIntentRecord{42d6e5e0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454091062372, Int=900000
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 4664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(4304a6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  904): Done.
,D/PowerUsageService( 4664): call getInstance()
,D/ConnectivityService(  904): Setting timer for 720seconds
D/PowerUsageList:PowerUsageHelper( 4664): MY_DEBUG = false
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(44657130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44657130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44633340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=989185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44633340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(445f6530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{443d9318: PendingIntentRecord{42c6da68 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1002970, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{443d69e0: PendingIntentRecord{436d9aa0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454091138086, Int=0
,D/PMS     (  904): acquireWL(44586780): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1404 10028 null
,D/PMS     (  904): releaseWL(44586780): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/SmartSyncUtils( 4664): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(4457c220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
D/PMS     (  904): releaseWL(4457c220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  904): releaseWL(445f6530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): acquireWL(44543e08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4664 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4664): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4664): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4664): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4664): SettingOnTime = 1454133600000, randomSettingOnTime = 1454131807000
,D/SmartSyncScreenOnOffTimeReceiver( 4664): SettingOffTime = 1454112000000, randomSettingOffTime = 1454114157000
,D/SmartSyncScreenOnOffTimeReceiver( 4664): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4664): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4664): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(44543e08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  904): acquireWL(444ac6d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1404 10028 null
,D/GCM     ( 1404): Message class mow
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1404/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1404/10028)
,D/PMS     (  904): releaseWL(444ac6d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): acquireWL(4448d320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1404 10028 null
,D/PMS     (  904): releaseWL(4448d320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=7 [290][21][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(4446aab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4446aab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4446a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1049184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4446a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(444521f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(444521f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44451e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1109185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44451e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(443e26a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(443e26a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(443dfde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1169185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(443dfde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(443c6350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(443c6350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(443a5178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1229184, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(443a5178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43fc5ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43fc5ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(439dab18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4257c1d0: PendingIntentRecord{42575570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1289185, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439dab18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),D/CustomizationManager( 4743): ====startRecUseTime====
D/htc.customization.log.level( 4743):  is 
W/CustomizationLogLevel( 4743): Level value is invalid, use default level 2
D/CustomizationManager( 4743):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4743): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4743): Parsing tag category name = system
I/CustomizationCIDLoader( 4743): Parsing tag category name = application
I/CustomizationCIDLoader( 4743): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4743): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4743): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4743): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4743): Parsing tag category name = Settings
D/CustomizationManager( 4743):  Read CID file spent 0.153 (s)
D/CustomizationManager( 4743):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4743): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4743): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4743): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4743): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4743, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=4414
I/ActivityManager(  904): Killing 4414:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  904):   Force finishing activity ActivityRecord{443bef28 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  904): Copying FileAsset 0x69f3da80 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 4414 uid 10189
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  904): WIN DEATH: Window{42d089f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  904): Client connection lost with reason: 4
I/dalvikvm-heap( 4054): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1864): Unregistering com.test.thalitest
E/acms    ( 1864): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1516): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(434a07d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1516 10028 null
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(434a07d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Scheme: "mms"
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
D/PackageBroadcastService( 2835): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/cutils-trace( 4743): Error opening trace file: No such file or directory (2)
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4759 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/PackageManager(  904):   Scheme: "mmsto"
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4759): install
I/MultiDex( 4759): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4759): loading existing secondary dex files
I/MultiDex( 4759): load found 1 secondary dex files
I/MultiDex( 4759): install done
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4775 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2835): CP2 sync disabled
I/Icing   ( 2835): doRemovePackageData com.test.thalitest
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2835, uid=10028, userID:0
D/PMS     (  904): acquireWL(442bdc78): PARTIAL_WAKE_LOCK  Icing 0x1 2835 10028 null
I/ProviderInstaller( 4759): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  904): releaseWL(442bdc78): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4775): install
I/MultiDex( 4775): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4775): loading existing secondary dex files
I/MultiDex( 4775): load found 1 secondary dex files
I/MultiDex( 4775): install done
I/ProviderInstaller( 4775): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1384): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  904): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1384): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
D/Process (  904): killProcessQuiet, pid=4078
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4078:com.google.android.gm/u0a107 (adj 15): empty #17
I/IcingCorporaProvider( 2913): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4797 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Recipient 4078
E/SQLiteLog( 2913): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2913): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6360cbb8
W/dalvikvm( 2913): threadid=14: thread exiting with uncaught exception (group=0x41e56e30)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidRuntime( 2913): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2913): Process: com.google.android.googlequicksearchbox:search, PID: 2913
E/AndroidRuntime( 2913): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2913): 	at cid.d(PG:186)
E/AndroidRuntime( 2913): 	at clo.g(PG:594)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2913): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2913): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2913): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2913): 	at clr.tL(PG:827)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2913): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/SQLiteDatabase( 4759): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4759): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4759): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4759): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4759): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4759): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4759): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4759): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4759): threadid=12: thread exiting with uncaught exception (group=0x41e56e30)
E/AndroidRuntime( 4759): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4759): Process: com.google.android.gms.drive, PID: 4759
E/AndroidRuntime( 4759): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4759): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4759): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4759): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4759): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4759): 	at ctn.run(SourceFile:985)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 2913): killProcess, pid=2913
D/Process ( 2913): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
D/Process ( 4759): killProcess, pid=4759
D/Process ( 4759): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4759
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4759) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2913
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2913): Died!
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2913) has died.
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4797): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4797): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4797): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4797): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4797): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4797): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4797): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4797): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4797): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4797): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4797): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4797): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4797): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4797): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4797): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4797): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4797): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4797): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4797): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4797): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4797): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4797): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4797): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4797): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4797): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4797): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4797): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4797): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4797): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4797): threadid=11: thread exiting with uncaught exception (group=0x41e56e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4797): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4797): Process: com.google.android.apps.docs, PID: 4797
E/AndroidRuntime( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4797): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4797): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4797): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4797): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4797): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
W/PackageManager(  904): Unable to load service info ResolveInfo{44461b10 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4797): killProcess, pid=4797
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4815 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4797): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4797): 	at dalvik.system.NativeStart.main(Native Method)
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
I/ActivityManager(  904): Recipient 4797
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  904): killProcessQuiet, pid=4480
I/ActivityManager(  904): Killing 4480:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4797) has died.
I/ActivityManager(  904): Recipient 4480
W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4828 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4815): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4815): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4815): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4815): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4815): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4815): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4815): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4815): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4815): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4815): threadid=10: thread exiting with uncaught exception (group=0x41e56e30)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4815): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4815): Process: com.android.keychain, PID: 4815
E/AndroidRuntime( 4815): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4815): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4815): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4815): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4815): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4815): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4815): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4815): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4815): killProcess, pid=4815
D/Process ( 4815): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454091438311.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
I/ActivityManager(  904): Recipient 4815
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 4815) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10450ms
D/AppTag  ( 4828): getInstance(Context context)
D/AppTag  ( 4828): getInstance(Context context)
D/AppTag  ( 4828): onCreate()
D/PMS     (  904): acquireWL(434a4100): PARTIAL_WAKE_LOCK  AsyncService 0x1 4054 10160 null
I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4846 uid=10098 gids={50098, 3003, 5012}
I/dalvikvm-heap( 4054): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@42319d90 +
I/Prism.WidgetManager( 1273): onLoadItems() +
D/PMS     (  904): releaseWL(434a4100): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 4846): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4846 dbg=false s=true
I/DeviceManagement( 4846): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4846): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4846): WorkflowService: Starting workflow service
I/DeviceManagement( 4846): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@422ba2e0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4846): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4846): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4846): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4846): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4860 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4846): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4846): SessionStateController: Checking invariants...
D/Documents( 4860): Loading roots for com.android.providers.downloads.documents
D/Documents( 4860): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4860): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4860): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4860): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4860): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4860): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4860): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4860): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4860): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4860): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4860): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4860): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4860): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4860): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4860): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4860): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4860): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4860): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4860): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4860): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4860): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4860): threadid=1: thread exiting with uncaught exception (group=0x41e56e30)
D/Process (  904): killProcessQuiet, pid=4290
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/AndroidRuntime( 4860): FATAL EXCEPTION: main
E/AndroidRuntime( 4860): Process: com.android.documentsui, PID: 4860
E/AndroidRuntime( 4860): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4860): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4860): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4860): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4860): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4860): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4860): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4860): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4860): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4860): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4860): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4860): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4860): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4860): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4860): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4860): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4860): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4860): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4860): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4860): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4860): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4860): 	... 10 more
I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4874 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  904): Killing 4290:com.google.android.music:main/u0a154 (adj 15): empty #17
E/ActivityManager(  904): App crashed! Process: com.android.documentsui
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1404): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process (  904): killProcessQuiet, pid=4510
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  904): Killing 4510:com.google.android.setupwizard/u0a78 (adj 15): empty #17
I/ActivityManager(  904): Recipient 4290
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.music (pid 4290): Died!
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454091438593.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/Process ( 4860): killProcess, pid=4860
D/Process ( 4860): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Recipient 4510
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Recipient 4860
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.documentsui (pid 4860) has died.
D/ExternalStorage( 4874): After updating volumes, found 1 active roots
D/GCM     ( 1404): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast

```
