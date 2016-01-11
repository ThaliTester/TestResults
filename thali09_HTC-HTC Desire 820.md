#### Test 549702617cfd775_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  907): Waited long enough for: ServiceRecord{43209c80 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4459): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4459): ====startRecUseTime====
D/htc.customization.log.level( 4459):  is 
W/CustomizationLogLevel( 4459): Level value is invalid, use default level 2
D/CustomizationManager( 4459):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4459): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4459): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4459): Parsing tag category name = system
I/CustomizationCIDLoader( 4459): Parsing tag category name = application
I/CustomizationCIDLoader( 4459): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4459): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4459): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4459): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4459): Parsing tag category name = Settings
D/CustomizationManager( 4459):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4459):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4459): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4459): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4459): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4459): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4459
D/PMS     (  907): acquireHCC(4254d978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(424e0ea8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6c9c5d60 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1113382992
D/PMS     (  907): acquireWL(4242eb58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c5df38
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4470 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4470): Copying FileAsset 0x5c8f4428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
V/WebViewChromiumFactoryProvider( 4470): Binding Chromium to main looper Looper (main, tid 1) {41b4a600}
I/LibraryLoader( 4470): Expected native library version number "",actual native library version number ""
I/chromium( 4470): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4470): Initializing chromium process, renderers=0
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4255eb00:true
D/PMS     (  907): acquireWL(426b7cd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  907): acquireWL(42679668): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  907): releaseWL(426b7cd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4470): 1102466136: getState(). Returning 12
I/Adreno-EGL( 4470): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4470): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4470): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4470): Local Branch: 
I/Adreno-EGL( 4470): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4470): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4470):                  aa63bbd948f41d15fc72f585e
W/chromium( 4470): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4470): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4470): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4470): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4470): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4470): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4470): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4470): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4470): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4470): CordovaWebView is running on device made by: HTC
,W/AwContents( 4470): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1273
,W/ResourceType( 4470): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4470): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b96308, mServedView=org.apache.cordova.engine.SystemWebView{41b5bf70 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  907): Enable input method client, pid=4470
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4470): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +285ms
D/PMS     (  907): releaseWL(4242eb58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4470): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4470): JniHelper::setJavaVM(0x41628048), pthread_self() = 1662973296
,D/JX-Cordova( 4470): jxcore cordova android initializing
,V/LightsService(  907): setLight #0: color=#23
,V/LightsService(  907): setLight #0: color=#20
,V/LightsService(  907): setLight #0: color=#19
,V/LightsService(  907): setLight #0: color=#14
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 11.582MB for 95956-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 11.776MB for 215890-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 11.951MB for 323830-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 12.223MB for 485740-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 13.223MB for 1092904-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 14.094MB for 1639352-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 15.449MB for 2459024-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 17.483MB for 3688532-byte allocation
,I/SensorManager(  907): mEventCount = 1201
,W/jxcore-log( 4470): Initializing JXcore engine
,W/jxcore-log( 4470): JXcore engine is ready
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
D/PMS     (  907): releaseHCC(4254d978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(424e0ea8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4470): Starting JXcore engine
,W/jxcore-log( 4470): Platform android
W/jxcore-log( 4470): 
,W/jxcore-log( 4470): Process ARCH arm
W/jxcore-log( 4470): 
,I/jxcore-log( 4470): JXcore Cordova bridge is ready!
I/jxcore-log( 4470): 
,W/jxcore-log( 4470): JXcore engine is started
,I/chromium( 4470): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4470): Toggling radios to true
I/jxcore-log( 4470): 
,D/BluetoothAdapter( 4470): enable(): BT is already enabled..!
,D/WifiManager( 4470): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1379
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4470): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
,D/WifiManager( 4470): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): TDLS: Tear down peers
,I/wpa_supplicant( 1136): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4470, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 4470): Radios toggled
I/jxcore-log( 4470): 
I/jxcore-log( 4470): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4470): 
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1136): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1136): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d62bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1136): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1136): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0),+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1136): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(424fa708): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/WifiNative-wlan0(  907): doBoolean: RECONNECT
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): Fast associate: Old scan results
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21303 mDataStallAlarmIntent=PendingIntent{43ba2140: PendingIntentRecord{41b56858 android broadcastIntent}}
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  907): releaseWL(42679668): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
,D/ConnectivityService(  907): resetConnections(wlan0, 3)
,V/NativeCrypto( 1346): Read error: ssl=0x64072008: I/O error during system call, Connection timed out
D/libc    (  366): [NET] entry_id:3   entry:0xb7afe108  removed 
D/libc    (  366): [NET] entry_id:4   entry:0xb7afe2f0  removed 
D/libc    (  366): [NET] entry_id:1   entry:0xb7afe428  removed 
D/libc    (  366): [NET] entry_id:5   entry:0xb7afdfd8  removed 
D/libc    (  366): [NET] entry_id:2   entry:0xb7afe4f0  removed 
D/libc    (  366): [NET] entry_id:6   entry:0xb7af9f88  removed 
D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
,V/NativeCrypto( 1346): SSL shutdown failed: ssl=0x64072008: I/O error during system call, Broken pipe
D/PMS     (  907): acquireWL(43375f40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/PMS     (  907): acquireWL(42687ff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1346/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/PMS     (  907): releaseWL(43375f40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1136): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
,D/PMS     (  907): releaseWL(42687ff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4521 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/PMS     (  907): acquireWL(432bb520): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(432bb520): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4323/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4323/10100)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
V/Tethering(  907): bSetPropertyMultiRAB:false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,I/MusicStore( 4521): Database version: 95
,W/ContextImpl( 4521): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4521): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4521, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4521): Registered
,I/MediaRouter( 4521): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4521/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2424/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4541 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4521): getSelectedRoute
,I/NetworkMonitor( 4521): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4521/10154)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4521, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ACRA    ( 4541): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  907): killProcessQuiet, pid=3862
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4541): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4541): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  907): acquireWL(437af140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Killing 3862:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/PMS     (  907): releaseWL(437af140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Recipient 3862
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4541): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4541): Preparing secondary program dexes.
V/DexLibLoader( 4541): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4541): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4541): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4541): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4541): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4541): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4541): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4541): Dex already copied
D/OdexVerifier( 4541): Odex verification is skipped.
V/DexLibLoader( 4541): Creating class loader
V/DexLibLoader( 4541): Finished creating class loader
V/DexLibLoader( 4541): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4541): Dex already copied
D/OdexVerifier( 4541): Odex verification is skipped.
,V/DexLibLoader( 4541): Creating class loader
,V/DexLibLoader( 4541): Finished creating class loader
V/DexLibLoader( 4541): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4541): Dex already copied
D/OdexVerifier( 4541): Odex verification is skipped.
,V/DexLibLoader( 4541): Creating class loader,
V/DexLibLoader( 4541): Finished creating class loader
V/DexLibLoader( 4541): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4541): Dex already copied
D/OdexVerifier( 4541): Odex verification is skipped.
,V/DexLibLoader( 4541): Creating class loader
,V/DexLibLoader( 4541): Finished creating class loader
,V/DexLibLoader( 4541): Verifying classes from secondary dexes.
,D/DexLibLoader( 4541): DexLibLoader.ensureDexLoaded took 17 ms,
,W/dalvikvm( 4541): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 3
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 1
I/wpa_supplicant( 1136): wpa_s->is_screen_on 1
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): selected network = 1
D/wpa_supplicant( 1136): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d644e8  current_ssid=0x0
D/wpa_supplicant( 1136): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1136): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1136): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1136): check if in concurrent case
,I/wpa_supplicant( 1136): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1136): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1136): RSN: PMKSA cache search - network_ctx=0xb8d644e8 try_opportunistic=0
D/wpa_supplicant( 1136): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1136): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1136): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1136): nl80211: Set mode ifindex 22 iftype 2 (STATION)
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1136): nl80211: Unsubscribe mgmt frames handle 0xb8d63718 (mode change)
D/wpa_supplicant( 1136): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d63718
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8d63718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1136):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 1136):   * freq=2412
D/wpa_supplicant( 1136):   * Auth Type 0
D/wpa_supplicant( 1136):   * WPA Versions 0x2
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1136): nl80211: Connect request send successfully
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (489) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
,I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000108211173
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000108211195
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000108211200
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55,
I/wpa_supplicant( 1136): tsf=0000000108211187
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108211173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 108211195, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 108211200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108211187, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Connect event
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1136): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1136): Add randomness: count=10 entropy=4
,I/wpa_supplicant( 1136): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on association
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=1,
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1136): EAPOL: enable timer tick
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1136): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d639f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 10,
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f76b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1136): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1136): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1136): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1136): set send_ind_to_ndc = 0
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1136): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1136): EAPOL authentication completed successfully
,I/wpa_supplicant( 1136): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/dalvikvm( 4541): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 1
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(441c3db0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426584b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426584b8 target=com.android.internal.util.StateMachine$SmHandler }
,W/dalvikvm( 4541): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4541): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4541): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):BaseAnalyticsConfig( 4541): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4541): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4256
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4256:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4256
,D/WifiService(  907): Client connection lost with reason: 4
D/AutoSetting( 1381): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4590 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1381/10055)
,D/AutoSetting( 1381): Util - no network available!
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1381/10055)
D/AutoSetting( 1381): service - onCreate()
D/AutoSetting( 1381): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1381): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  907): request 425a5258 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1381): service - mHandler: cancel location update
D/AutoSetting( 1381): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4590): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4590): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4590): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4590): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4605 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4590/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4590/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4590/10079)
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,W/fb4a(:<default>):UserScope( 4541): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4541): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,W/fb4a(:<default>):UserScope( 4541): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(441c3db0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1136): Change stage from stage0 to stage3
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1136): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4619 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4162
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,I/ActivityManager(  907): Killing 4162:com.google.android.talk/u0a111 (adj 15): empty #17
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21305 delay=15s
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WISPrService( 3823): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1119): WifiActivity: 3
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
I/ActivityManager(  907): Recipient 4162
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424da638
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  907): acquireWL(4278bfe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4590/10079)
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43b6b560): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4278bfe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(436a4b58): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452520854769 min interval config: 0 actual interval: 47725
D/PMS     (  907): releaseWL(43b6b560): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
,I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2178): Checking schedule, now: 1452520902511 next: 1452520884568
I/CheckinService( 2178): active receiver: enabled
E/dalvikvm( 4541): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4541): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2178, uid=10029, userID:0
E/dalvikvm( 4541): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4541): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4541): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4541): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4541): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4541): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4541): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4541): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4541): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I//system/bin/ip(  366): RTNETLINK answers: No such process
I/logwrapper(  366): /system/bin/ip terminated by exit(2)
W/dalvikvm( 4541): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4541): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4541): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4541): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4541): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4541): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4541): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/CheckinService( 2178): Preparing to send checkin request
I/EventLogService( 2178): Accumulating logs since 1452520850805
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,W/GAV2    ( 4619): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4619): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 9.966MB for 84664-byte allocation
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 9.991MB for 39954-byte allocation
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 10.067MB for 79892-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 10.094MB for 28144-byte allocation
,D/wpa_supplicant( 1136): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1136): EAPOL: disable timer tick
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4619/10151)
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4619): Binding Chromium to main looper Looper (main, tid 1) {41b53fe8}
,I/LibraryLoader( 4619): Expected native library version number "",actual native library version number ""
,I/chromium( 4619): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4619): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(441b5498): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
,D/PMS     (  907): acquireWL(441b5448): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
,E/AudioManagerAndroid( 4619): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(441b5498): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4541): Grow heap (frag case) to 10.261MB for 75760-byte allocation
,I/Adreno-EGL( 4619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4619): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4619): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4619): Local Branch: 
I/Adreno-EGL( 4619): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4619): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4619):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4665 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433be288 u0 ReceiverList{431fded8 4541 com.facebook.katana/10027/u0 remote:41e60208}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{433be288 u0 ReceiverList{431fded8 4541 com.facebook.katana/10027/u0 remote:41e60208}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4327d650 u0 ReceiverList{431f9570 4541 com.facebook.katana/10027/u0 remote:41e34dd8}}
,I/NSApplication( 4619): Starting up...
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4665): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4619/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4619/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4665): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4665): install
,I/MultiDex( 4665): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
I/MultiDex( 4665): loading existing secondary dex files
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4665): load found 3 secondary dex files
,I/MultiDex( 4665): install done
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4092/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4092/10160)
,D/Process (  907): killProcessQuiet, pid=4291
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 4291:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4291
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4665): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4665): VFY: unable to resolve instance field 36
,W/dalvikvm( 4665): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,V/JNIHelp ( 4665): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  907): acquireWL(42688688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42688688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4541): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ProviderInstaller( 4665): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/LocationInitializer( 2178): Restart initialization of location
,D/AuthorizationBluetoothService( 1346): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1346): Proximity feature is not enabled.
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1225): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 4665): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4665): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4665): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4665): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4665): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  907): acquireWL(4249ad58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4249ad58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,I/WVCdm   (  375): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  375): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  375): CdmEngine::OpenSession
,I/WVCdm   (  375): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  375): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4665): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  375): PrepareKeyRequest: nonce=198193783
,I/WVCdm   (  375): CdmEngine::CloseSession
,W/Settings( 4665): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): releaseWL(424fa708): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4590/10079)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4323/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3927/10053)
D/PMS     (  907): acquireWL(425e7ae0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4521/10154)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
I/NetworkMonitor( 4521): type=WIFI subType= reason=null isConnected=true
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4323/10100)
D/PMS     (  907): acquireWL(42515e68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42515e68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(425e7ae0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2424/10021)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/AutoSetting( 1381): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4590): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1381): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4590): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1381/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4665/10029)
D/AutoSetting( 1381): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1381): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1381): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1381): service - handleMessage() setting current location null
D/AutoSetting( 1381): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1381): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1381/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4619/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4092/10160)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4092/10160)
D/PMS     (  907): acquireWL(42434a90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452520854769 min interval config: 0 actual interval: 48810
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42434a90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4092): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4665): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4665): Local Branch: 
I/Adreno-EGL( 4665): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4665): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4665):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  375): CdmEngine::OpenSession
I/WVCdm   (  375): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  375): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  375): PrepareKeyRequest: nonce=2010554794
,I/WVCdm   (  375): CdmEngine::CloseSession
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42236190
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42236190, eanble = 0, strlen(mName) = 59
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe37d0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@4269b8f8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2178): [NET] getaddrinfo-, 1
,D/libc    ( 2178): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =5891 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 276
D/libc    (  366): [NET]res_nsend:resplen=84
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2178): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 314ms
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43755270)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  907): wakingUp
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  907): Disable input method client, pid=4470
D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting -2
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/PMS     (  907): acquireWL(43b70868): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(43b70868): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  907): onScreenOn
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/CheckinTask( 2178): Sending checkin request (12349 bytes)
,D/MtpService( 2424): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2424): [MTP][onReceive]-
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  907): acquireWL(426af2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1381): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  907): releaseWL(426af2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): acquireWL(43bce338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  907): releaseWL(43bce338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TetherSettings( 3823): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/        ( 3823): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3823): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3823): Cust_ConnectToPC   : spcsc>false
D/        ( 3823): Cust_ConnectToPC   : IPT>true
D/        ( 3823): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3823): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3823): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3823): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1381): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 3823): onReceive:android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21306 delay=15s
I/ClockThread( 1119): stop update clock
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:On
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): BG scan when screen On
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): Match BG scan, scan!
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3823): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3823):  defaultType:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/WIFI_ICON( 1119): WifiActivity: 2
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  375): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  907): updateScreenOn: false
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4724 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  907): acquireWL(435f4958): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(435f4958): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4724): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(43864078): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43864078): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1757): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1757): onScreenOn: 1452520904647
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1757): onScreenOn: 1452520904648
,D/SmartSyncUtils( 4724): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(440971e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4724 1000 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe37d0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fe37d0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@4269b8f8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(43845768): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/PMS     (  907): releaseWL(440971e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21306 mDataStallAlarmIntent=PendingIntent{426f8c60: PendingIntentRecord{41b56858 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/PMS     (  907): acquireWL(431e2868): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/SmartSyncUtils( 4724): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=4323
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4323:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4323
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{42440a50 u0 com.test.thalitest/.MainActivity t2}
,W/fb4a(:<default>):UserScope( 4541): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4541): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:Off
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1136): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  375): ParamSet string: screen_state=off
W/ContextImpl( 4724): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/SmartSyncUtils( 4724): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4724): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4724): getMobilePolicyEnabled, result = true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  907): New client listening to asynchronous messages
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269b8f8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269b8f8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4269b8f8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4269b8f8
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42623d70 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42623d70 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4541): Called registerBroadcastReceiver twice.
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(4333a538): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4333a538): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(438ecd20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1757): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1757): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1757): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1757): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1757): onScreenOff
D/PMS     (  907): releaseWL(438ecd20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1381): service - mHandler: cancel location update
,D/AutoSetting( 1381): service -           changes count: 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =cd0f +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4541/10027)
,D/PMS     (  907): acquireWL(43a21038): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4521 10154 null
,W/ContextImpl( 4521): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4521, uid=10154, userID:0
W/ContextImpl( 4521): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4521): Conditions not met for autocaching.
,I/MusicLeanback( 4521): Stop autocaching.
D/PMS     (  907): releaseWL(43a21038): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  907): releaseWL(441b5448): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0],
D/PMS     (  907): releaseWL(431e2868): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-5,5
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1136): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1136): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1136): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (489) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000113240809
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000113240839
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000108211200
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000113240829
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ####
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43bcfef8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43bcfef8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@43bcfef8 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 113240809, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 113240839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 108211200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 113240829, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=172
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=7 [26][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,I/CheckinTask( 2178): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2178): Checking schedule, now: 1452520907129 next: 1453043844125
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,I/CheckinService( 2178): Checking schedule, now: 1452520907145 next: 1453043844125
,I/CheckinService( 2178): active receiver: disabled
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,D/CheckinService( 2178): Recording last checkin time for package unspecified as 1452520907151
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(436a4b58): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/PMS     (  907): acquireWL(438c4df8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/GCM     ( 1346): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1346): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1346): [NET] getaddrinfo-,err=8
D/libc    ( 1346): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1346): [NET] getaddrinfo-, 1
D/libc    ( 1346): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =1f18 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 67
D/libc    (  366): [NET]res_nsend:resplen=79
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1346): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1346): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1346): [NET] getaddrinfo-,err=8,
,D/libc    ( 1346): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1346): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  907): acquireWL(44148328): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  907): releaseWL(438c4df8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1346/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(44148328): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42ca28e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1346/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1346/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
D/PMS     (  907): releaseWL(42ca28e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4619): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=10 [10][1][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/jxcore-log( 4470): Test app app.js loaded
I/jxcore-log( 4470): 
,I/Choreographer( 4470): Skipped 528 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4470): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4470): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b5bf70 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  907): releaseWL(43845768): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4470): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  907): killProcessQuiet, pid=4339
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4339:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4339
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1535): service - handleMessage() stop self
,D/AutoSetting( 1535): service - onDestroy() END
,D/AutoSetting( 1535): service - handleMessage() quit looper
,I/ActivityManager(  907): Killing 4310:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4310
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4310
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4764 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4764): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4764): MmsConfig.loadMmsSettings
,W/dalvikvm( 4764): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4764): VFY: unable to resolve instance field 36
,W/dalvikvm( 4764): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4788 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4764, uid=10111, userID:0
,W/Settings( 4764): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4764, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4764, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4764, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4764, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4764, uid=10111, userID:0
,D/MessageFrequencyProvider( 4788): onCreate
D/PMS     (  907): acquireWL(423c6738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4764 10111 null
,V/GetPrviateResource( 4788): GetPrviateResource
D/MmsCustomizationProvider( 4788): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4788): GetPrviateResource
I/[PluginManager]RegisterService( 1381): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1381): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/MmsCustomizationProvider( 4788): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2833): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4764): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4764): MmsConfig.loadFromDatabase
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,E/Babel   ( 4764): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4764): MmsConfig.loadFromResources
,E/Babel   ( 4764): canonicalizeMccMnc: invalid mccmnc nullnull
,D/PMS     (  907): acquireWL(41c88248): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
I/Babel   ( 4764): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/PMS     (  907): releaseWL(423c6738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  907): killProcessQuiet, pid=4363
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ProviderInstaller( 4764): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  907): Killing 4363:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4363
,D/MessageCustFlag( 4788): sense_version=6.0
,D/BTAccessoryUtil( 4788): createReceiver
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BTAccessoryUtil( 4788): registerReceiver return intent = null
D/MessageCustFlag( 4788): sku_id=99
W/SystemReader( 4788): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4788): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4788): networkCode: 
,D/MessageCustFlag( 4788): sku_id=99
D/MmsConfig( 4788): SIE smsPri: null
,D/MmsConfig( 4788): networkCode: 
D/HtcTelephonyCapability( 4788): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4788): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4788): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4788): Cannot find qct_8960_interface, use default value instead
,W/PackageManager(  907): Unable to load service info ResolveInfo{42559040 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  907): releaseWL(41c88248): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4296ee20): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4092): Grow heap (frag case) to 15.201MB for 1821008-byte allocation
D/PMS     (  907): acquireWL(425a8178): PARTIAL_WAKE_LOCK  AsyncService 0x1 4092 10160 null
,I/dalvikvm-heap( 4092): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(425a8178): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): releaseWL(4296ee20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(43255220): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): releaseWL(43255220): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  907): acquireWL(425d9268): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425d9268): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,D/PMS     (  907): acquireWL(425e70c0): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2178): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2178): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(42485510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42485510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/PMS     (  907): acquireWL(44378688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(44183158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(44378688): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(44183158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,I/IcingCorporaProvider( 2833): UpdateCorporaTask done [took 383 ms] updated apps [took 383 ms] 
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PMS     (  907): acquireWL(43213f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43213f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41be3db0 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2178): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41be3db0 -
,I/Icing   ( 2178): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(425e70c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,D/PhoneApp( 1245): -- N3 =0
,D/Process (  907): killProcessQuiet, pid=3927
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3927:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3927
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Messaging( 4788): mNeedToUpdateDate2 start
,D/MmsConfig( 4788): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4788): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4788): 
D/MmsAsyncWorkHandler( 4788): HM tk = 20001
,D/ReportIndicatorCache( 4788): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4788): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b61340
,I/Messaging( 4788): mccmnc> 
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1245):  phoneType = -1
D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4788): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4788): [DraftCache/1] refresh
,D/MmsConfig( 4788): networkCode: 
,D/Messaging( 4788): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4788): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4788): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4788): createReceiver
,D/MessageCustFlag( 4788): sense_version=6.0
D/Jerry   ( 4788): start to preload cursor >>>>>>>
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TelephUtils( 1245): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1245): Update uri=content://mms, match=0
,V/MmsProvider( 1245): selection=st=129 AND m_type!=134
D/Messaging( 4788): mNeedToUpdateDate2: false
,D/Messaging( 4788): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4788): TransactionService is going to be woken up.
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): sku_id=99
,V/TransactionService( 4788): 1-Creating TransactionService
V/TransactionService( 4788): onStartCommand: 1
,D/MmsSystemEventReceiver( 4788): unRegisterForConnectionStateChanges
V/TransactionService( 4788): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4788): Loading previous transactions.
,D/DraftCache( 4788): [DraftCache/475] rebuildCache
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1245): device_type: 1
,D/Messaging( 4788): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1245):  phoneType = -1
D/TransactionService( 4788): Force set service start id to 1
V/TransactionService( 4788): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4788): unRegisterForConnectionStateChanges
,D/TransactionService( 4788): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4788): Destroying TransactionService
V/TransactionService( 4788): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1245): URI_DRAFT
D/Messaging( 4788): ViewCache CreatePreload
,D/Messaging( 4788): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4788): hasDraft() = false mNeedNotifyChange = true
,D/Cust_MMSMS( 4788): _has_set_default_values_2=true
,D/DraftCache( 4788): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4788): 
D/MmsAsyncWorkHandler( 4788): HM tk = 20002
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): sku_id=99
,D/MsgPreferenceUtils( 4788): def_index: 0
,D/MsgPreferenceUtils( 4788): globalIndex = 1
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): sku_id=99
D/MsgPreferenceUtils( 4788): phone state: true
D/MsgPreferenceUtils( 4788): sd state: false
,D/MsgPreferenceUtils( 4788): vIndex = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{432159a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4764): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(425e6ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{441b9f30: PendingIntentRecord{42a944b0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126445, Int=0
,D/PMS     (  907): acquireWL(43216120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425e6ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=16 [12][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(426a81b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43216120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426a81b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(431d9a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(431d9a50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43337c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43312f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43213d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4255c1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4206ee80: PendingIntentRecord{423c2720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126633, Int=0
,I/VacuumService( 1225): Vacuum at: now=1452520920020 tag=VacuumService
D/PMS     (  907): releaseWL(4255c1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(43337c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43312f48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44129458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
D/PMS     (  907): releaseWL(43213d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(44129458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43ad86d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(43ad86d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441584f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(441584f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1136): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1136): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1136): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1136): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1136): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: N,ot restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1136): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1136): Add randomness: count=27 entropy=16
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1136): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1136): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1136): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000130382437
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136,): level=-55
I/wpa_supplicant( 1136): tsf=0000000130382476
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000130382506
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000130382464
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000130382517
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000130382527
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 130382437, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 130382476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 130382506, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 130382464, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 130382517, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 130382527, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42c12790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(42c12790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1381): service - mHandler: update timezone
,D/AutoSetting( 1535): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1535): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1535): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1535): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1535): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1535): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1535): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1535): service - mHandler: update timezone
D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1535): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1535): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1535): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1535): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41cf49b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  907): acquireWL(43616998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42cf7510: PendingIntentRecord{42ce0160 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142034, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
,D/PMS     (  907): releaseWL(43616998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c49258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/AutoSetting( 1381): service - handleMessage() stop self
,D/AutoSetting( 1381): service - handleMessage() quit looper
,D/AutoSetting( 1381): service - onDestroy() END
,D/PMS     (  907): acquireWL(42af2580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42af2580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4385fd80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c49258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43875f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(43875f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 12787 seconds from now (1452520935923)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42cd03c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41f7ddc0: PendingIntentRecord{42593050 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142790, Int=0
D/PMS     (  907): acquireWL(43293388): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42cd03c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =ad8e +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0,
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
W/dalvikvm( 1225): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 49
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =3559 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  366): [NET]res_nsend:resplen=87
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=10 [39][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4385fd80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(436ac140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(436ac140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4390ce90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1346 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=50 [2][1][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1346/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(4390ce90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1136): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1136): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1136): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1136): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( ,1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1136): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1136): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1136): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1136): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1,
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000147522891
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000147522916
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000130382506
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000130382464
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000147522938
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000147522948
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 147522891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 147522916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 130382506, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 130382464, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 147522938, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 147522948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(43293388): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  907): killProcessQuiet, pid=4394
,I/ActivityManager(  907): Killing 4394:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4394
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43850360 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1136): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1136): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1136): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1136): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1136): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1,136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1136): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1136): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1136): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1136): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1136): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000164883908
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000164883946
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000164883956
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000164883934
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
,I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000164883975
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000164883966
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 164883908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 164883946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 164883956, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 164883934, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 164883975, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 164883966, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/AutoSetting( 1535): service - handleMessage() stop self
,D/AutoSetting( 1535): service - onDestroy() END
,D/AutoSetting( 1535): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4409
,I/ActivityManager(  907): Killing 4409:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4409
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43559488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43559488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1119): closing low battery warning: level=100
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 1346): disconnect managed GoogleApiClient
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1136): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1136): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1136): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1136): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1136): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1,136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1136): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1136): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1136): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1136): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1136): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000182203911
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
,I/wpa_supplicant( 1136): tsf=0000000182203948
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000182203960
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000182203937
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000182203980
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000182203970
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 182203911, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 182203948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 182203960, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 182203937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 182203980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 182203970, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): add 6 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4331c7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4206ee80: PendingIntentRecord{423c2720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186634, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4331c7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(431ee238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431ee238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1136): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1136): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1136): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1136): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136):, Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1136): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1136): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1136): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1136): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000199543451
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000199543487
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000199543497
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_suppli,cant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000199543476
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000199543507
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000182203970
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 199543451, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 199543487, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 199543497, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 199543476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 199543507, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 182203970, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1136): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1136): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1136): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supp,licant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1136): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1136): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1136): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (632) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000216893802
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000216893827
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000216893838
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000199543476
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000216893848
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 216893802, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 216893827, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 216893838, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 199543476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 216893848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4368be70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{42405568: PendingIntentRecord{436682a0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229533, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4873 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{426959b8: PendingIntentRecord{426dd9a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452521005863, Int=10800000
,D/PMS     (  907): releaseWL(4368be70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4873/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/Process (  907): killProcessQuiet, pid=4053
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4053:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  907): Recipient 4053
,D/PMS     (  907): acquireWL(42973458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{4268c2e0: PendingIntentRecord{441f88a0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231106, Int=120000
,V/AlarmManager(  907): sending alarm PendingIntent{437ce1c8: PendingIntentRecord{436682a0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231310, Int=0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025390
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025448
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025461
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025482
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025493
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026918
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030073
,D/PMS     (  907): releaseWL(42973458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  907): acquireWL(429c8e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(429c8e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1136): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1136): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1136): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant,( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-82
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1136): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1136): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1136): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (519) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000216893802
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000234082269
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-82
I/wpa_supplicant( 1136): tsf=0000000234082281
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000234082292
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 216893802, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 234082269, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 234082281, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 234082292, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): add 4 to mScanResults
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(436119a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4206ee80: PendingIntentRecord{423c2720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246634, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436119a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1136): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1136): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1136): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1136): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1136): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1136): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (519) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000251373851
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000251373878
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-81
I/wpa_supplicant( 1136): tsf=0000000251373889
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
,I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000234082292
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 251373851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 251373878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 251373889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 234082292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4415c478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4415c478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1136): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1136): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1136): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1136): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1136): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1136): Add randomness: count=102 entropy=91
D,/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (376) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000251373851
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000268723468
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-81
I/wpa_supplicant( 1136): tsf=0000000268723479
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 251373851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 268723468, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 268723479, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-94
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1136): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1136): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1136): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1136): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1136): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_i,e_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-94
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=109 entropy=98
D/wpa_supplicant( 1136): Add randomness: count=110 entropy=99
,D/wpa_supplicant( 1136): Add randomness: count=111 entropy=100
D/wpa_supplicant( 1136): Add randomness: count=112 entropy=101
D/wpa_supplicant( 1136): Add randomness: count=113 entropy=102
D/wpa_supplicant( 1136): Add randomness: count=114 entropy=103
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (765) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000286073875
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000286073914
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-81
I/wpa_supplicant( 1136): tsf=0000000286073924
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000286073903
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
,I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000286073934
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-94
I/wpa_supplicant( 1136): tsf=0000000286073944
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ####
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 286073875, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 286073914, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 286073924, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 286073903, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 286073934, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -94, frequency: 2462, timestamp: 286073944, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-94], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(43844e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43844e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-93
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=115 entropy=104
D/wpa_supplicant( 1136): Add randomness: count=116 entropy=105
D/wpa_supplicant( 1136): Add randomness: count=117 entropy=106
D/wpa_supplicant( 1136): Add randomness: count=118 entropy=107
D/wpa_supplicant( 1136): Add randomness: count=119 entropy=108
D/wpa_supplicant( 1136): Add randomness: count=120 entropy=109
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136):, clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-93
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=121 entropy=110
D/wpa_supplicant( 1136): Add randomness: count=122 entropy=111
D/wpa_supplicant( 1136): Add randomness: count=123 entropy=112
D/wpa_supplicant( 1136): Add randomness: count=124 entropy=113
D/wpa_supplicant( 1136): Add randomness: count=125 entropy=114
D/wpa_supplicant( 1136): Add randomness: count=126 entropy=115
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA sube,lement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (765) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000286073875
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000303433729
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-81
I/wpa_supplicant( 1136): tsf=0000000303433739
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000303433718
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000303433748
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-93
I/wpa_supplicant( 1136): tsf=0000000303433758
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 286073875, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 303433729, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 303433739, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 303433718, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 303433748, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -93, frequency: 2462, timestamp: 303433758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  72, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-93], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(439e3168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4206ee80: PendingIntentRecord{423c2720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306634, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(439e3168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(427058e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427058e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-93
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=127 entropy=116
D/wpa_supplicant( 1136): Add randomness: count=128 entropy=117
D/wpa_supplicant( 1136): Add randomness: count=129 entropy=118
D/wpa_supplicant( 1136): Add randomness: count=130 entropy=119
D/wpa_supplicant( 1136): Add randomness: count=131 entropy=120
D/wpa_supplicant( 1136): Add randomness: count=132 entropy=121
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136):, clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-93
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=133 entropy=122
D/wpa_supplicant( 1136): Add randomness: count=134 entropy=123
D/wpa_supplicant( 1136): Add randomness: count=135 entropy=124
D/wpa_supplicant( 1136): Add randomness: count=136 entropy=125
D/wpa_supplicant( 1136): Add randomness: count=137 entropy=126
D/wpa_supplicant( 1136): Add randomness: count=138 entropy=127
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (765) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-47
I/wpa_supplicant( 1136): tsf=0000000320764057
,I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000320764093
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2452
I/wpa_supplicant( 1136): level=-81
I/wpa_supplicant( 1136): tsf=0000000320764103
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-55
I/wpa_supplicant( 1136): tsf=0000000320764083
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
,I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000320764113
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-93
I/wpa_supplicant( 1136): tsf=0000000320764122
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 320764057, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 320764093, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 320764103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 320764083, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 320764113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -93, frequency: 2462, timestamp: 320764122, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  78, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  9 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  72, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-93], Tx: 13, Freq:  9 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/jxcore-log( 4470): --= Surplus to requirements =--,
I/jxcore-log( 4470): 
I/jxcore-log( 4470): ****TEST TOOK:  ms ****
I/jxcore-log( 4470): 
,I/jxcore-log( 4470): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4470): 
,E/cutils-trace( 4897): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4897): ====startRecUseTime====
D/htc.customization.log.level( 4897):  is 
,W/CustomizationLogLevel( 4897): Level value is invalid, use default level 2
,D/CustomizationManager( 4897):  Read ACC file spent 0.112 (s)
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4897): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4897): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4897): Parsing tag category name = system
I/CustomizationCIDLoader( 4897): Parsing tag category name = application
I/CustomizationCIDLoader( 4897): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4897): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4897): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4897): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4897): Parsing tag category name = Settings
D/CustomizationManager( 4897):  Read CID file spent 0.167 (s)
D/CustomizationManager( 4897):  All configurations done spent 0.167 (s)
W/HtcNativeFlag( 4897): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4897): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4897): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4897): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4897, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,I/ActivityManager(  907): Killing 4470:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  907): killProcessQuiet, pid=4470
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{42440a50 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x63ac2558 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4470 uid 10389
,W/PackageSettings(  907): Skipping PackageSetting{42204d28 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{42443a88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/PMS     (  907): acquireWL(438c5338): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): releaseWL(438c5338): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SQLiteConnectionPool( 2178): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,D/VoicemailCleanupService( 1287): Cleaning up data for package: com.test.thalitest
I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/[PluginManager]RegisterService( 1381): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1381): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,I/IcingCorporaProvider( 2833): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4913 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,W/Parcel  ( 1258): Reading a NULL string not supported here.
,D/PMS     (  907): acquireWL(43d0ae38): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2833): UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4913): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4913): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4913): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4913): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4913): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4913): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4913): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4913): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4913): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4913): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4913): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4913): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4913): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4913): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4913): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4913): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4913): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4913): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4913): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4913): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4913): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4913): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4913): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4913): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4913): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4913): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4913): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4913): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4913): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4913): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4913): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4913): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4913): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4913): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4913): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4913): threadid=11: thread exiting with uncaught exception (group=0x41720e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4913): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4913): Process: com.google.android.apps.docs, PID: 4913
E/AndroidRuntime( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4913): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4913): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4913): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4913): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4913): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4913): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4913): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4913): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4913): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4913): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4913): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4913): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteDatabase.open,Database(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4913): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4913): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4913): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4913): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4913): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4913): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4913): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4913): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4913): killProcess, pid=4913
D/Process ( 4913): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4931 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4913
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=4442
,I/ActivityManager(  907): Killing 4442:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4913) has died.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4442
,W/ContextImpl( 4931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4944 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4931): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4931): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4931): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4931): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4931): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4931): threadid=10: thread exiting with uncaught exception (group=0x41720e30)
E/AndroidRuntime( 4931): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4931): Process: com.android.keychain, PID: 4931
E/AndroidRuntime( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4931): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4931): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4931): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4931): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4944): getInstance(Context context)
,D/AppTag  ( 4944): getInstance(Context context)
,D/AppTag  ( 4944): onCreate()
,D/Process ( 4931): killProcess, pid=4931
,D/Process ( 4931): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452521116458.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  907): Recipient 4931
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4931) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(422f6bc0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4092 10160 null
,D/PMS     (  907): releaseWL(422f6bc0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4117): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,D/AccountUtils( 2178): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e43c378
,W/dalvikvm( 2178): threadid=44: thread exiting with uncaught exception (group=0x41720e30)
,E/AndroidRuntime( 2178): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2178): Process: com.google.android.gms, PID: 2178
E/AndroidRuntime( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2178): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2178): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2178): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2178): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6534a790
,E/DriveAsyncService( 2178): disk I/O error (code 3850)
E/DriveAsyncService( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2178): 	at java.lang.Thread.run(Thread.java:864)
,I/LocationSettingsChecker( 2178): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms
,D/Process ( 2178): killProcess, pid=2178
,D/Process ( 2178): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/ActivityManager(  907): Recipient 2178
I/ActivityManager(  907): Process com.google.android.gms (pid 2178) has died.
D/PMS     (  907): handleWLDeath(43d0ae38): PARTIAL_WAKE_LOCK  Icing 0x1
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10997ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10996ms
,I/ActivityManager(  907): Resuming delayed broadcast
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10985ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10985ms
,E/SQLiteLog( 1346): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1346): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x640295d0
,W/dalvikvm( 1346): threadid=1: thread exiting with uncaught exception (group=0x41720e30)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41be3db0 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20981ms
E/AndroidRuntime( 1346): FATAL EXCEPTION: main
E/AndroidRuntime( 1346): Process: com.google.process.gapps, PID: 1346
E/AndroidRuntime( 1346): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1346): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1346): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1346): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1346): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1346): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1346): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1346): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1346): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1346): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1346): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1346): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1346): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1346): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1346): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1346): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1346): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1346): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1346): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1346): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1346): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1346): 	... 10 more
,E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,D/Process ( 1346): killProcess, pid=1346
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4974 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1346): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,W/PackageManager(  907): Unable to load service info ResolveInfo{426b0230 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/DeviceManagement( 4974): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4974 dbg=false s=true
,I/DeviceManagement( 4974): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4974): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  907): Recipient 1346
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Process com.google.process.gapps (pid 1346) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30805ms
,I/DeviceManagement( 4974): WorkflowService: Starting workflow service
,I/DeviceManagement( 4974): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b80ea8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4974): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4974): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4974): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4974): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4988 uid=10099 gids={50099, 3003, 5012}

```
