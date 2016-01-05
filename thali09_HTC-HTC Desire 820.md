#### Test 54970261fc259e9_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{441bd9d8 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4394): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4394): ====startRecUseTime====
D/htc.customization.log.level( 4394):  is 
W/CustomizationLogLevel( 4394): Level value is invalid, use default level 2
D/CustomizationManager( 4394):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4394): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4394): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4394): Parsing tag category name = system
I/CustomizationCIDLoader( 4394): Parsing tag category name = application
I/CustomizationCIDLoader( 4394): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4394): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4394): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4394): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4394): Parsing tag category name = Settings
D/CustomizationManager( 4394):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4394):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4394): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4394): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4394): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4394): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4394
D/PMS     (  905): acquireHCC(41bc97b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42614a50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62dc01f8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1105411664
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fcd8e0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  905): acquireWL(423e1bb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4405 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4405): Copying FileAsset 0x5c7c2420 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4405): Binding Chromium to main looper Looper (main, tid 1) {41b4ddb0}
I/LibraryLoader( 4405): Expected native library version number "",actual native library version number ""
I/chromium( 4405): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4405): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(425730d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): acquireWL(424efb00): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423aa030:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): releaseWL(424efb00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4405): 1102462480: getState(). Returning 12
I/Adreno-EGL( 4405): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4405): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4405): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4405): Local Branch: 
I/Adreno-EGL( 4405): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4405): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4405):                  aa63bbd948f41d15fc72f585e
W/chromium( 4405): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4405): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4405): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4405): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4405): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4405): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4405): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4405): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4405): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4405): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/AwContents( 4405): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +276ms
,W/ResourceType( 4405): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4405): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b954c0, mServedView=org.apache.cordova.engine.SystemWebView{41b5b128 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Disable input method client, pid=1272
,I/InputMethodManagerService(  905): Enable input method client, pid=4405
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4405): nativeOnDraw failed; clearing to background color.
D/PMS     (  905): releaseWL(423e1bb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4405): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4405): JniHelper::setJavaVM(0x41628048), pthread_self() = 1662993048
,D/JX-Cordova( 4405): jxcore cordova android initializing
,V/LightsService(  905): setLight #0: color=#25
,V/LightsService(  905): setLight #0: color=#22
,V/LightsService(  905): setLight #0: color=#1b
,V/LightsService(  905): setLight #0: color=#14
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 11.634MB for 95956-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 11.711MB for 143930-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 11.827MB for 215890-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 11.999MB for 323830-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 12.266MB for 485740-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 13.270MB for 1092904-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 14.178MB for 1639352-byte allocation
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 15.513MB for 2459024-byte allocation
,E/libc    ( 4405): mmap fail (pid 4405, tid 4405, size 0, flags 0x1, errno 22(Invalid argument))
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(41bc97b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42614a50): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4405): Grow heap (frag case) to 17.617MB for 3688532-byte allocation
,W/jxcore-log( 4405): Initializing JXcore engine
,W/jxcore-log( 4405): JXcore engine is ready
,W/jxcore-log( 4405): Starting JXcore engine
,W/jxcore-log( 4405): Platform android
W/jxcore-log( 4405): 
,W/jxcore-log( 4405): Process ARCH arm
W/jxcore-log( 4405): 
,I/jxcore-log( 4405): JXcore Cordova bridge is ready!
I/jxcore-log( 4405): 
,W/jxcore-log( 4405): JXcore engine is started
,D/PMS     (  905): releaseWL(425730d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/chromium( 4405): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4405): Toggling radios to true
I/jxcore-log( 4405): 
,D/BluetoothAdapter( 4405): enable(): BT is already enabled..!
,D/WifiManager( 4405): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 915
,W/Settings:Agent(  905): Process.myUid(): 1000
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4405, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 4(ms)
D/WifiManager( 4405): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4405): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): TDLS: Tear down peers
I/wpa_supplicant( 1173): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4405): Radios toggled
I/jxcore-log( 4405): 
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1173): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1173): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb743cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1173): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false,
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1173): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  905): [isWifi] getHotspotEnabled: false,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(4253fca8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19977 mDataStallAlarmIntent=PendingIntent{4258d780: PendingIntentRecord{42571f88 android broadcastIntent}}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): Fast associate: Old scan results
I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3791): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3791): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3791): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3791): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NativeCrypto( 1369): Read error: ssl=0x66255270: I/O error during system call, Connection timed out
V/NativeCrypto( 1369): SSL shutdown failed: ssl=0x66255270: I/O error during system call, Broken pipe
D/libc    (  362): [NET] entry_id:4   entry:0xb7ab9c20  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb7abe2e8  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb7abe478  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb7ac2f70  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb7ac2aa8  removed 
D/libc    (  362): [NET] entry_id:3   entry:0xb7ac2e00  removed 
D/libc    (  362): [NET] entry_id:8   entry:0xb7ac2c80  removed 
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  905): acquireWL(426ef428): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/PMS     (  905): acquireWL(42c6d7a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/PMS     (  905): releaseWL(42c6d7a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1369/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/PMS     (  905): releaseWL(426ef428): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4462 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  905): acquireWL(44245b80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
D/PMS     (  905): releaseWL(44245b80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4234/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4234/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,I/MusicStore( 4462): Database version: 95
,W/ContextImpl( 4462): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4462): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4462): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4462): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4462): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4462, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4462): Registered
,I/MediaRouter( 4462): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4462/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2390/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4482 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4462): getSelectedRoute
,I/NetworkMonitor( 4462): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4462/10154)
,D/ACRA    ( 4482): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  905): killProcessQuiet, pid=4170
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4462, uid=10154, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4269f218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/ActivityManager(  905): Killing 4170:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4482): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4482): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  905): releaseWL(4269f218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SystemClassLoaderAdder( 4482): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4482): Preparing secondary program dexes.
V/DexLibLoader( 4482): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4482): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4482): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4482): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4482): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4482): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4482): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4482): Dex already copied
D/OdexVerifier( 4482): Odex verification is skipped.
,V/DexLibLoader( 4482): Creating class loader
V/DexLibLoader( 4482): Finished creating class loader
V/DexLibLoader( 4482): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4482): Dex already copied
D/OdexVerifier( 4482): Odex verification is skipped.
,V/DexLibLoader( 4482): Creating class loader,
V/DexLibLoader( 4482): Finished creating class loader
V/DexLibLoader( 4482): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4482): Dex already copied
D/OdexVerifier( 4482): Odex verification is skipped.
V/DexLibLoader( 4482): Creating class loader
V/DexLibLoader( 4482): Finished creating class loader
V/DexLibLoader( 4482): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4482): Dex already copied
D/OdexVerifier( 4482): Odex verification is skipped.
V/DexLibLoader( 4482): Creating class loader
V/DexLibLoader( 4482): Finished creating class loader
V/DexLibLoader( 4482): Verifying classes from secondary dexes.
D/DexLibLoader( 4482): DexLibLoader.ensureDexLoaded took 16 ms
,I/ActivityManager(  905): Recipient 4170
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  905): mEventCount = 1050
,W/dalvikvm( 4482): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1173): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 3
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 1
I/wpa_supplicant( 1173): wpa_s->is_screen_on 1
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): selected network = 1
D/wpa_supplicant( 1173): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb743e4e8  current_ssid=0x0
D/wpa_supplicant( 1173): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1173): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1173): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1173): check if in concurrent case
I/wpa_supplicant( 1173): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doStrin,g: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1173): RSN: PMKSA cache search - network_ctx=0xb743e4e8 try_opportunistic=0
D/wpa_supplicant( 1173): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1173): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1173): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1173): nl80211: Unsubscribe mgmt frames handle 0xb743d718 (mode change)
D/wpa_supplicant( 1173): nl80211: Subscribe to mgmt frames with non-AP handle 0xb743d718
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb743d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1173):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173):   * freq=2412
D/wpa_supplicant( 1173):   * Auth Type 0
D/wpa_supplicant( 1173):   * WPA Versions 0x2
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1173): nl80211: Connect request send successfully
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0,
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (489) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000107931193
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000107931210
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-79
I/wpa_supplicant( 1173): tsf=0000000107931214
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-54
I/wpa_supplicant( 1173): tsf=0000000107931205
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 107931193, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 107931210, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 107931214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 107931205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Connect event
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1173): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on association
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1173): EAPOL: enable timer tick
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1173): getPrivFuncNum +	
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1173): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): Get randomness: len=32 entropy=5
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb743d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb1b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    broadcast key
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1173): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1173): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
E/wpa_supplicant( 1173): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1173): set send_ind_to_ndc = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1173): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 1173): EAPOL authentication completed successfully
I/wpa_supplicant( 1173): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  905): updateConnectedAP...,
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3791): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3791): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 1
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4369b0a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4237ef48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4237ef48 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,W/dalvikvm( 4482): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4482): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4482): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4482): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4482): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4482): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4080
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4080:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4511 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,D/AutoSetting( 1342): Util - no network available!
,D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1342): service - mHandler: cancel location update
,D/AutoSetting( 1342): service -           changes count: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,I/ActivityManager(  905): Recipient 4080
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MobileConnectivityChangeReceiver( 4511): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4511): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4511): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4511): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4524 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4202
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4202:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10079)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4202
,W/fb4a(:<default>):UserScope( 4482): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4482): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4482): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  905): killProcessQuiet, pid=4234
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4539 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 4234:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4482): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  905): Recipient 4234
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4482): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4482): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4482): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4482): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4482): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4482): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4482): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4482): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4482): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4482): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4482): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4482): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4482): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4482): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4482): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4482): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4482): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4482): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4539): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 9.919MB for 39954-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 9.996MB for 79892-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 10.076MB for 84664-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,V/WebViewChromiumFactoryProvider( 4539): Binding Chromium to main looper Looper (main, tid 1) {41b530e8}
,I/LibraryLoader( 4539): Expected native library version number "",actual native library version number ""
,I/chromium( 4539): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4539): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(44140490): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,E/AudioManagerAndroid( 4539): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(4423bf70): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): releaseWL(44140490): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/wpa_supplicant( 1173): EAPOL: startWhen --> 0
D/wpa_supplicant( 1173): EAPOL: disable timer tick
,I/Adreno-EGL( 4539): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4539): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4539): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4539): Local Branch: 
I/Adreno-EGL( 4539): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4539): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4539):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4539): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3554/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3554/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,I/iu.Environment( 2159): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2159): num queued entries: 0
,I/iu.UploadsManager( 2159): num updated entries: 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,I/iu.SyncManager( 2159): NEXT; no task
,D/Process (  905): killProcessQuiet, pid=4257
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
I/ActivityManager(  905): Killing 4257:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4257
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d660a0 u0 ReceiverList{43856120 4482 com.facebook.katana/10027/u0 remote:4383f320}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d660a0 u0 ReceiverList{43856120 4482 com.facebook.katana/10027/u0 remote:4383f320}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433a0ad8 u0 ReceiverList{433a0a78 4482 com.facebook.katana/10027/u0 remote:432f23c8}}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): acquireWL(437d1428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(437d1428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4482): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4482): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(4369b0a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19979 delay=15s
,D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,D/WISPrService( 3791): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  905): WAN detection
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@424d6e78
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(43d015b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10079)
,D/PMS     (  905): acquireWL(43c523e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2159): Checkin interval check for package: unspecified last checkin: 1452011122074 min interval config: 0 actual interval: 49364
D/PMS     (  905): acquireWL(43c52318): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c523e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2159): Checking schedule, now: 1452011171443 next: 1452011152052
,I/CheckinService( 2159): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2159, uid=10029, userID:0
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2159): Preparing to send checkin request
,I/EventLogService( 2159): Accumulating logs since 1452011118057
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43d015b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2159): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2159): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2159/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4614 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4614): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4614): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4614): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4614): install
,I/MultiDex( 4614): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4614): loading existing secondary dex files
,I/MultiDex( 4614): load found 3 secondary dex files
,I/MultiDex( 4614): install done
,W/dalvikvm( 4614): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4614): VFY: unable to resolve instance field 36
,W/dalvikvm( 4614): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4614): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4614): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4614): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1220): callingUid 10029, callindPid: 1220
,D/LocationInitializer( 2159): Restart initialization of location
D/AuthorizationBluetoothService( 1369): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1369): Proximity feature is not enabled.
,E/MDM     ( 1220): [111] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 4614): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4614): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4614): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4614): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4614): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
D/PMS     (  905): acquireWL(425ca870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(425ca870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=358261324
,D/NativeLibraryUtils( 4614): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  369): CdmEngine::CloseSession
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42277040
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  905): setLight #0: color=#0
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42277040, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ac040
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41c6d750
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  905): releaseWL(4253fca8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 309ms
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): nativeSetInteractive:false
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): nativeSetInteractive:false done
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
D/PMS     (  905): acquireWL(435cdab8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): releaseWL(435cdab8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  905): nativeSetAutoSuspend:true done
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,D/NfcService( 1253): applyRouting -2
,I/NetworkMonitor( 4462): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3869/10053)
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(436f1e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(436f1e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4405
D/PMS     (  905): acquireWL(436e36e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4462/10154)
D/PMS     (  905): releaseWL(436e36e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(437ed0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1533/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(437ed0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d99438)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMN     (  905): wakingUp
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(4367dc58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  905): onScreenOn
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
I/HtcPowerSaver(  905): >> updateStatus
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): releaseWL(4367dc58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2390/10021)
,D/NfcService( 1253): applyRouting - 0
E/ExternalAccountType( 1328): Unsupported attribute readOnly
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/NfcService( 1253): applyRouting -2
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(43c29058): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  905): releaseWL(43c29058): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/MtpService( 2390): [MTP][onReceive]+android.intent.action.USER_PRESENT
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/MtpService( 2390): [MTP][onReceive]-
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19980 delay=15s
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1116): stop update clock
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:On
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WIFI_ICON( 1116): WifiActivity: 0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  369): ParamSet string: screen_state=on
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/MobileConnectivityChangeReceiver( 4511): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4511): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
,D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1342): service - onStartCommand() screen is off, don't request location
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/NetworkPolicy(  905): updateScreenOn: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/AutoSetting( 1342): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1342): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3554/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3554/10160)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43d69be0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2159): Checkin interval check for package: unspecified last checkin: 1452011122074 min interval config: 0 actual interval: 50510
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43d69be0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43616068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43616068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2159, uid=10029, userID:0
D/PMS     (  905): acquireWL(437e78a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1736): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): onScreenOn: 1452011172605
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1736): onScreenOn: 1452011172605
D/PMS     (  905): releaseWL(437e78a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ac040
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
I/iu.Environment( 2159): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2159): num queued entries: 0
W/SensorService(  905): pid=905, uid=1000
I/iu.UploadsManager( 2159): num updated entries: 0
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
I/iu.SyncManager( 2159): NEXT; no task
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421ac040, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41c6d750
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(4358b490): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WVCdm   (  369): PrepareKeyRequest: nonce=276639751
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/AlarmManager(  905): ACTION_SCREEN_OFF
,I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/AutoSetting( 1342): receiver - intent: android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19980 mDataStallAlarmIntent=PendingIntent{42586de0: PendingIntentRecord{442951b0 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:Off
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/PMS     (  905): acquireWL(41f0b048): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/PMS     (  905): acquireWL(42c668a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 3791): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3791): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3791): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3791): Cust_ConnectToPC   : spcsc>false
D/        ( 3791): Cust_ConnectToPC   : IPT>true
D/        ( 3791): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3791): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3791): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3791): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3791): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
,D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =6834 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,I/PSReceiver( 3791): onReceive:android.intent.action.USER_PRESENT
,V/SRS_Proc(  369): ParamSet string: screen_state=off
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3791): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3791): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3791):  defaultType:0
D/NetworkPolicy(  905): updateScreenOn: false
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/ContactMessageStore( 1238): start background delete task...
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/WVCdm   (  369): CdmEngine::CloseSession
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
D/PMS     (  905): releaseWL(41f0b048): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4657 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/Settings( 4614): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=50 [2][1][0]
,I/Adreno-EGL( 4614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4614): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4614): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4614): Local Branch: 
I/Adreno-EGL( 4614): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4614): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4614):                  aa63bbd948f41d15fc72f585e
,D/AutoSetting( 1342): service - mHandler: cancel location update
,D/AutoSetting( 1342): service -           changes count: 0
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(43d665c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43d665c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(44240490): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(44240490): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1736): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1736): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1736): onScreenOff
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,I/Adreno-EGL( 4614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4614): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4614): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4614): Local Branch: 
I/Adreno-EGL( 4614): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4614): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4614):                  aa63bbd948f41d15fc72f585e
D/PMS     (  905): acquireWL(43d5bb58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
,D/PMS     (  905): releaseWL(43d5bb58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c6d750
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c6d750, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:,
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c6d750, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c6d750
D/WifiService(  905): New client listening to asynchronous messages
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b8c60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b8c60 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4614/10029)
,I/Adreno-EGL( 4614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4614): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4614): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4614): Local Branch: 
I/Adreno-EGL( 4614): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4614): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4614):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,W/fb4a(:<default>):UserScope( 4482): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4482): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/CheckinRequestBuilder( 2159): Classify the device as Phone.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 2159): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2159): [NET] getaddrinfo-,err=8
D/libc    ( 2159): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2159): [NET] getaddrinfo-, 1
D/libc    ( 2159): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =83ed +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 236
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 34
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2159): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,D/libc    ( 2159): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2159): [NET] getaddrinfo-,err=8
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
W/ActivityManager(  905): Activity pause timeout for ActivityRecord{41fe07c8 u0 com.test.thalitest/.MainActivity t2}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/libc    ( 2159): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2159): [NET] getaddrinfo-,err=8
D/libc    ( 2159): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2159): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,I/CheckinTask( 2159): Sending checkin request (12082 bytes)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4482): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4482/10027)
,D/PMS     (  905): acquireWL(43730268): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/PMS     (  905): releaseWL(42c668a0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(43730268): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43849e68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43849e68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4423bf70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  905): acquireWL(42cae690): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4462 10154 null
,W/ContextImpl( 4462): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4462, uid=10154, userID:0
,D/PMS     (  905): releaseWL(42cae690): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4462): Conditions not met for autocaching.
I/MusicLeanback( 4462): Stop autocaching.
W/ContextImpl( 4462): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/CheckinRequestBuilder( 2159): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2159): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2159/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=8 [25][2][0]
,I/CheckinRequestBuilder( 2159): Classify the device as Phone.
,I/CheckinTask( 2159): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2159): Checking schedule, now: 1452011173757 next: 1452534110752
,I/CheckinService( 2159): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2159, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
I/CheckinService( 2159): Checking schedule, now: 1452011173784 next: 1452534110752
,I/CheckinService( 2159): active receiver: disabled
,D/CheckinService( 2159): Recording last checkin time for package unspecified as 1452011173789
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2159, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43c52318): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2159/10029)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =5697 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175,
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!,
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4,
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState,
,I/GAV2    ( 4539): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4405): Test app app.js loaded
I/jxcore-log( 4405): 
,I/Choreographer( 4405): Skipped 509 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4405): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4405): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4405): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b5b128 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(4358b490): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  905): killProcessQuiet, pid=4275
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4275:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=4221
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4221:com.htc.cs.dm/u0a98 (adj 15): empty #18
,I/ActivityManager(  905): Recipient 4275
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4221
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1632): service - handleMessage() stop self
,D/AutoSetting( 1632): service - onDestroy() END
,D/AutoSetting( 1632): service - handleMessage() quit looper
,I/ActivityManager(  905): Killing 4305:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4305
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4305
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4699 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4699): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4699): VFY: unable to resolve instance field 36
,W/dalvikvm( 4699): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/Babel   ( 4699): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4699): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4699): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4722 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4699, uid=10111, userID:0
,W/Settings( 4699): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4699, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4699, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4699, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4699, uid=10111, userID:0
,D/MessageFrequencyProvider( 4722): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4699, uid=10111, userID:0
D/PMS     (  905): acquireWL(431eeda8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4699 10111 null
,D/MmsCustomizationProvider( 4722): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4722): GetPrviateResource
,V/GetPrviateResource( 4722): GetPrviateResource
,I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
,I/ProviderInstaller( 4699): Installed default security provider GmsCore_OpenSSL
,I/IcingCorporaProvider( 2828): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4722): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/PackageManager(  905): Unable to load service info ResolveInfo{42534808 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Babel   ( 4699): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4699): MmsConfig.loadFromDatabase
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(423afc50): PARTIAL_WAKE_LOCK  Icing 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42610d70): PARTIAL_WAKE_LOCK  AsyncService 0x1 3554 10160 null
D/PMS     (  905): releaseWL(42610d70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/Babel   ( 4699): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4699): MmsConfig.loadFromResources
,E/Babel   ( 4699): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4699): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  905): releaseWL(431eeda8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/MessageCustFlag( 4722): sense_version=6.0
,D/BTAccessoryUtil( 4722): createReceiver
,D/BTAccessoryUtil( 4722): registerReceiver return intent = null
,D/PackageBroadcastService( 2159): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/MessageCustFlag( 4722): sku_id=99
W/SystemReader( 4722): Cannot find message_ambs_application_id, use default value instead
I/PackageBroadcastService( 2159): Null package name or gms related package.  Ignoreing.
D/Messaging( 4722): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4722): networkCode: 
D/MessageCustFlag( 4722): sku_id=99
D/MmsConfig( 4722): SIE smsPri: null
D/MmsConfig( 4722): networkCode: 
D/HtcTelephonyCapability( 4722): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4722): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4722): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4722): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2159): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(4252a720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4252a720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(441419b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(441419b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423cd468): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(423cd468): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43223d68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43223d68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2828): UpdateCorporaTask done [took 402 ms] updated apps [took 402 ms] 
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  905): killProcessQuiet, pid=3869
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3869:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3869
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41be3cd8 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2159): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2159): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  905): releaseWL(423afc50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41be3cd8 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/Messaging( 4722): mNeedToUpdateDate2 start
,D/MmsConfig( 4722): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4722): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4722): 
D/MmsAsyncWorkHandler( 4722): HM tk = 20001
D/ReportIndicatorCache( 4722): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4722): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b60530
,I/Messaging( 4722): mccmnc> 
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/DraftCache( 4722): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4722): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4722): networkCode: 
,D/Messaging( 4722): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
,D/MessageCustFlag( 4722): sense_version=6.0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Jerry   ( 4722): start to preload cursor >>>>>>>
,D/DraftCache( 4722): [DraftCache/472] rebuildCache
D/PhoneStorageUtil( 4722): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4722): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4722): createReceiver
,D/Messaging( 4722): mNeedToUpdateDate2: false
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1238):  phoneType = -1
D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
,D/Messaging( 4722): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4722): TransactionService is going to be woken up.
,V/TransactionService( 4722): 1-Creating TransactionService
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
V/TransactionService( 4722): onStartCommand: 1
,D/MmsSystemEventReceiver( 4722): unRegisterForConnectionStateChanges
V/TransactionService( 4722): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4722): Loading previous transactions.
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1238): device_type: 1
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1238): URI_DRAFT
D/TransactionService( 4722): Force set service start id to 1
V/TransactionService( 4722): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4722): unRegisterForConnectionStateChanges
,D/TransactionService( 4722): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4722): Destroying TransactionService
D/Messaging( 4722): ViewCache CreatePreload
,D/Messaging( 4722): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4722): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/DraftCache( 4722): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4722): [DraftCache/472] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4722): 
D/MmsAsyncWorkHandler( 4722): HM tk = 20002
,D/Cust_MMSMS( 4722): _has_set_default_values_2=true
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4722): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1238): sku_id=99
,D/MsgPreferenceUtils( 4722): def_index: 0
,D/MsgPreferenceUtils( 4722): globalIndex = 1
D/MsgPreferenceUtils( 4722): phone state: true
D/MsgPreferenceUtils( 4722): sd state: false
,D/MsgPreferenceUtils( 4722): vIndex = 0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4699): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4327
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4327:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4327
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(433052f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43a3a698: PendingIntentRecord{437f17e0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=125900, Int=0
,D/PMS     (  905): releaseWL(433052f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43524620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [14][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(435c53a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(435c53a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43524620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c8a170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43c8a170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44079368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): acquireWL(437fb248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(441ddd00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1452011187612 tag=VacuumService
D/PMS     (  905): releaseWL(44079368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(437fb248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(436b1608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(436b1608): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43da5138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/PMS     (  905): releaseWL(441ddd00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43da5138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(437e5190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(437e5190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44135078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(44135078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43acebd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(441a5550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441a5550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43742e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43acebd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(436f0c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(436f0c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 7009 seconds from now (1452011188131)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =6f0a +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 4
D/libc    (  362): [NET]res_nsend:resplen=87
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(43742e90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43d59b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43d59b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43685500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43685500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(437cbf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(437cbf68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1342): service - mHandler: update timezone
,D/AutoSetting( 1632): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1632): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1632): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1632): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1632): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1632): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1632): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1632): service - mHandler: update timezone
,D/DotMatrix( 1521): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1632): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1632): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1632): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1632): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1521): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41f86198 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  905): acquireWL(426ce1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{4409ae20: PendingIntentRecord{43743518 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141351, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/PMS     (  905): releaseWL(426ce1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1342): service - handleMessage() stop self
,D/AutoSetting( 1342): service - handleMessage() quit looper
,D/AutoSetting( 1342): service - onDestroy() END
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  905): killProcessQuiet, pid=4342
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4342:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4342
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43828210 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(4265a210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4265a210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42700098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(42700098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1632): service - handleMessage() stop self
,D/AutoSetting( 1632): service - onDestroy() END
,D/AutoSetting( 1632): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=3977
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3977:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3977
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43d73db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d73db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43d58220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d58220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43cfb3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43c51c50: PendingIntentRecord{44138498 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229182, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4801 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{424cf3a0: PendingIntentRecord{424546f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452011276948, Int=10800000
,D/PMS     (  905): releaseWL(43cfb3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4801/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/Process (  905): killProcessQuiet, pid=4377
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4377:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4377
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43aa9918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{4372f1f8: PendingIntentRecord{44246518 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230971, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{435e3410: PendingIntentRecord{44138498 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231114, Int=0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(43aa9918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  905): acquireWL(42d41f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d41f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(431d5590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(431d5590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43c2ea98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c2ea98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43678ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43678ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43429bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43429bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4405): TAP version 13
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # multiplex can send data
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 1 String should be length:200
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # basic
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 2 sane
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # another
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 3 sane
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 4 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 5 null
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 6 (unnamed assert),
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 7 should be equal
I/jxcore-log( 4405): 
I/jxcore-log( 4405): ok 8 should not throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 9 (unnamed assert)
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 10 (unnamed assert)
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 11 should not throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 12 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 13 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 14 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # failed to get mobile documents path
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,D/PMS     (  905): acquireWL(4266b5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=338488, Int=0
,I/jxcore-log( 4405): ok 15 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,D/PMS     (  905): releaseWL(4266b5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4405): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 16 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 17 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 18 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #init should register the networkChanged event
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 19 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on null device name
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 20 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 21 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 22 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 23 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on negative port
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 24 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should throw on too large port
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 25 should throw
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 26 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 27 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 28 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 29 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 30 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 31 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 32 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 33 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 34 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 35 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 36 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 37 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 38 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 39 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 40 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 41 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 42 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 43 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): ok 44 should be equal
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # setup
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4405): 
,I/jxcore-log( 4405): # teardown
I/jxcore-log( 4405): 
,W/dalvikvm( 4405): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4405): threadid=1: thread exiting with uncaught exception (group=0x41720e30)
,E/AndroidRuntime( 4405): FATAL EXCEPTION: main
E/AndroidRuntime( 4405): Process: com.test.thalitest, PID: 4405
E/AndroidRuntime( 4405): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4405): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4405): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4405): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4405): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4405): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4405): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4405): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4405): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4405): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4405): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4405): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4405): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4405): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4405): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4405): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4405): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.test.thalitest
W/ActivityManager(  905):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  905): killProcessQuiet, pid=4511
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/Process ( 4405): killProcess, pid=4405
,D/Process ( 4405): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Killing 4511:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4511
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  905): channel '4256a000 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  905): channel '4256a000 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '4256a000 com.test.thalitest.MainActivity (s)'
I/WindowManager(  905): WINDOW DIED Window{4256a000 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  905): Recipient 4405
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.test.thalitest (pid 4405) has died.
D/WifiService(  905): Client connection lost with reason: 4
W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42f28b50 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  905): WIN DEATH: null
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4405 uid 10389
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(431fc5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(431fc5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(437188c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/PMS     (  905): releaseWL(437188c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(426b7030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426b7030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c276f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c276f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(432f40b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(432f40b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4361eaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=458488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4361eaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4349f570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4349f570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43c94f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=518488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c94f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43af2860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{437f12b8: PendingIntentRecord{44246518 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531119, Int=300000
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946,
,D/PMS     (  905): releaseWL(43af2860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42b01b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42b01b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44169180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=578489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44169180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43230ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43230ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44189bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44189bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1238): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1238): sku_id=99
D/ContactMessageStore( 1238): start background delete task...
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/PMS     (  905): acquireWL(435ebf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435ebf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(440e5340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440e5340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4413b198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4413b198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4433af40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=698488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4433af40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(442355e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(442355e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4415c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4415c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(440cc050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=758488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440cc050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e85a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PMS     (  905): releaseWL(43e85a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d374d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d374d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c69ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=818489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c69ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c54d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43c54d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43a54558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43a54558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-,
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4385b4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=878488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.656MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(4385b4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4383fb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderNotification, total:1
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/HeadsetPhoneState( 1547): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4383fb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/TetherSettings( 3791): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3791): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3791): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3791): Cust_ConnectToPC   : spcsc>false
D/        ( 3791): Cust_ConnectToPC   : IPT>true
,D/        ( 3791): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3791): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3791): Index of the first 1 = -1
W/Settings( 3791): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3791): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3791): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3791): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3791): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43601010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43601010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435a82e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41e07f00: PendingIntentRecord{424e1630 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786029, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{41dcf278: PendingIntentRecord{42547908 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=914491, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4369b1b0: PendingIntentRecord{42c771a8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452011410973, Int=1800000
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/PMS     (  905): acquireWL(435834d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4348bd68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): acquireWL(426bd350): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): releaseWL(435a82e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  905): acquireWL(41db1068): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(426bd350): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4201d818): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=10 [240][25][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/PMS     (  905): acquireWL(43fccef8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/EventLogService( 2159): Aggregate from 1452011171465 (log), 1452009610926 (data)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(435834d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(4348bd68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4259d868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4259d868): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42f2d670): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42f2d670): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): acquireWL(43bd79d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43bd79d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,D/PMS     (  905): releaseWL(41db1068): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(432216d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4201d818): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  905): releaseWL(432216d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360914661
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4359d1d8: PendingIntentRecord{435b1ca0 com.google.android.gms startService}}) : type=2 triggerAtTime=315360914661 win=-1 tElapsed=315360914661 maxElapsed=551880914660 interval=0 standalone=false
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42643408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43fccef8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  905): releaseWL(42643408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(43200008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=938488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43200008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43a8b420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/PMS     (  905): acquireWL(43d57b48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,V/AlarmManager(  905): sending alarm PendingIntent{41dcf278: PendingIntentRecord{42547908 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=944563, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,V/AlarmManager(  905): sending alarm PendingIntent{41f0a658: PendingIntentRecord{41e539c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452011997305, Int=900000
,D/PMS     (  905): acquireWL(440c3730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43d57b48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(440c3730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4657): call getInstance()
,D/PMS     (  905): releaseWL(43a8b420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4657): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(42f6ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42f6ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(436f5350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436f5350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  905): acquireWL(42c66488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42c66488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43203bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
V/AlarmManager(  905): sending alarm PendingIntent{4244f2f0: PendingIntentRecord{42cccc20 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452012072918, Int=0
,D/PMS     (  905): releaseWL(43203bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42608d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4657): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOnTime = 1452060000000, randomSettingOnTime = 1452058876000
,D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOffTime = 1452045600000, randomSettingOffTime = 1452049784000
,D/SmartSyncScreenOnOffTimeReceiver( 4657): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(42608d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(43733ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{442024b0: PendingIntentRecord{43ac8c70 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1011871, Int=0
,D/PMS     (  905): acquireWL(4357bf80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4357bf80): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43733ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(431d6ae8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024883
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025027
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025076
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025081
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025087
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025091
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027319
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027328
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360032946
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360914661
,D/PMS     (  905): releaseWL(431d6ae8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=20 [15][3][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(434c42a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434c42a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(432e3910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(432e3910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c1bec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c1bec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4422f088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1118488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.656MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(4422f088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4369d5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(4369d5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo,
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(438016a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438016a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(44209f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1178489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44209f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(435f9758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435f9758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(43d21dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1238488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d21dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43618708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43618708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(429a28b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1298488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.656MB for 50416-byte allocation
D/PMS     (  905): releaseWL(429a28b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e85578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e85578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4423cf90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4423cf90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4358ad08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1358489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4358ad08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43881860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43881860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43d67648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1418489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43d67648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44161528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44161528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42cdb350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1478488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.656MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(42cdb350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42ca7118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1547): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderNotification, total:0
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42ca7118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3791): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3791): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3791): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3791): Cust_ConnectToPC   : spcsc>false
D/        ( 3791): Cust_ConnectToPC   : IPT>true
,D/        ( 3791): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3791): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3791): Index of the first 1 = -1
W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3791): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3791): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3791): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3791): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4433af40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4433af40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(44253530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1538488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44253530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(442358f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(442358f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4422bc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1598488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4422bc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4422bb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4422bb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(442250b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1658489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(442250b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44225018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44225018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(441dbf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1718489, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.656MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(441dbf00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(441dbbf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(441dbbf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4419a408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1778488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4419a408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(44169a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44169a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(439e2df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1838488, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  905): Prepared write state in 26ms
,D/PMS     (  905): releaseWL(439e2df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2016-01-05-01-38-07.bin
,D/PMS     (  905): acquireWL(438900e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(438900e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4385c3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c5fbe8: PendingIntentRecord{41f85918 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1898489, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4385c3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4874): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4874): ====startRecUseTime====
D/htc.customization.log.level( 4874):  is 
W/CustomizationLogLevel( 4874): Level value is invalid, use default level 2
D/CustomizationManager( 4874):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4874): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4874): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4874): Parsing tag category name = system
I/CustomizationCIDLoader( 4874): Parsing tag category name = application
I/CustomizationCIDLoader( 4874): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4874): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4874): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4874): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4874): Parsing tag category name = Settings
D/CustomizationManager( 4874):  Read CID file spent 0.155 (s)
D/CustomizationManager( 4874):  All configurations done spent 0.155 (s)
W/HtcNativeFlag( 4874): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4874): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4874): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4874): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4874, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4462
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4539
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  905): Killing 4462:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  905): Killing 4539:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  905): killProcessQuiet, pid=4524
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  905): Killing 4524:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  905): Recipient 4539
W/asset   (  905): Copying FileAsset 0x65041140 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  905): Skipping PackageSetting{4220def8 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4462
D/MediaRouterService(  905): Client com.google.android.music (pid 4462): Died!
I/ActivityManager(  905): Recipient 4524
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  905): acquireWL(436ad330): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(436ad330): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
W/SQLiteConnectionPool( 2159): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/Process (  905): killProcessQuiet, pid=4614
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/ActivityManager(  905): Killing 4614:com.google.android.gms.unstable/u0a29 (adj 15): empty for 1800s
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/VoicemailCleanupService( 1285): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  905): Recipient 4614
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/IcingCorporaProvider( 2828): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4888 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(44127480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(44127480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): acquireWL(440dd998): PARTIAL_WAKE_LOCK  Icing 0x1 2159 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2828): UpdateCorporaTask done [took 470 ms] updated apps [took 470 ms] 
E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4888): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4888): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4888): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4888): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4888): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4888): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4888): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4888): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4888): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4888): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4888): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4888): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4888): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4888): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4888): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4888): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4888): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4888): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4888): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4888): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4888): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4888): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4888): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4888): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4888): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4888): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4888): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4888): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4888): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4888): threadid=11: thread exiting with uncaught exception (group=0x41720e30)
W/PackageManager(  905): Unable to load service info ResolveInfo{425675d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 4888): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4888): Process: com.google.android.apps.docs, PID: 4888
E/AndroidRuntime( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4888): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4888): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4888): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4888): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4888): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  905): Can't write: system_app_crash
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
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4907 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4888): killProcess, pid=4888
D/Process ( 4888): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4888
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4888) has died.
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/RemoteDisplayProvider(  905): start
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ContextImpl( 4907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4907): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4907): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4907): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4907): threadid=10: thread exiting with uncaught exception (group=0x41720e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4907): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4907): Process: com.android.keychain, PID: 4907
E/AndroidRuntime( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4907): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4907): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4921 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4907): killProcess, pid=4907
D/Process ( 4907): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452012976514.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Recipient 4907
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4907) has died.
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/AppTag  ( 4921): getInstance(Context context)
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4921): getInstance(Context context)
D/AppTag  ( 4921): onCreate()
D/PMS     (  905): acquireWL(42f286f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3554 10160 null
D/PMS     (  905): releaseWL(42f286f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4017): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2159): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2159): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2159): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2159): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2159): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2159): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2159): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2159): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2159): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2159): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x651a0dc8
E/SQLiteDBG( 2159): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66b6b720
W/dalvikvm( 2159): threadid=42: thread exiting with uncaught exception (group=0x41720e30)
E/DriveAsyncService( 2159): disk I/O error (code 3850)
E/DriveAsyncService( 2159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2159): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2159): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2159): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2159): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2159): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2159): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2159): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2159): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2159): Process: com.google.android.gms, PID: 2159
E/AndroidRuntime( 2159): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2159): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2159): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2159): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2159): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2159): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2159): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2159): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2159): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2159): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2159): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2159): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2159): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2159): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2159): killProcess, pid=2159
D/Process ( 2159): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Recipient 2159
I/ActivityManager(  905): Process com.google.android.gms (pid 2159) has died.
D/PMS     (  905): handleWLDeath(440dd998): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10997ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10997ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10994ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10993ms
E/SQLiteLog( 1369): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1369): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5cafa008
W/dalvikvm( 1369): threadid=1: thread exiting with uncaught exception (group=0x41720e30)
E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1369): FATAL EXCEPTION: main
E/AndroidRuntime( 1369): Process: com.google.process.gapps, PID: 1369
E/AndroidRuntime( 1369): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1369): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1369): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1369): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1369): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1369): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1369): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1369): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1369): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1369): 	... 10 more
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1369): killProcess, pid=1369
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4950 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1369): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 4950): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4950 dbg=false s=true
I/DeviceManagement( 4950): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4950): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4950): WorkflowService: Starting workflow service
I/DeviceManagement( 4950): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b7fef8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4950): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4950): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4950): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4950): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4964 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4950): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4950): SessionStateController: Checking invariants...
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41be3cd8 +
I/Prism.WidgetManager( 1272): onLoadItems() +
I/ActivityManager(  905): Recipient 1369
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.process.gapps (pid 1369) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20815ms
D/WifiService(  905): Client connection lost with reason: 4
D/Documents( 4964): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4964): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4964): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4964): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4964): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4964): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4964): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4964): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4964): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4964): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4964): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4964): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4964): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4964): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4964): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4964): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4964): threadid=1: thread exiting with uncaught exception (group=0x41720e30)
E/AndroidRuntime( 4964): FATAL EXCEPTION: main
E/AndroidRuntime( 4964): Process: com.android.documentsui, PID: 4964
E/AndroidRuntime( 4964): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4964): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4964): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4964): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4964): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4964): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4964): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4964): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4964): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4964): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4964): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4964): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4964): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4964): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4964): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4964): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4964): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4964): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4964): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4964): 	... 10 more
D/Documents( 4964): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  905): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4978 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ActivityManager(  905): App crashed! Process: com.android.documentsui
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4990 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452012977057.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4964): killProcess, pid=4964
D/Process ( 4964): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 4964
I/ActivityManager(  905): Process com.android.documentsui (pid 4964) has died.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4978): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/ExternalStorage( 4990): After updating volumes, found 1 active roots
W/dalvikvm( 4978): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/SQLiteDatabase( 4950): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4950): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4950): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4950): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4950): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4950): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4950): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4950): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4950): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4950): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4950): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4950): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4950): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4950): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel
```
