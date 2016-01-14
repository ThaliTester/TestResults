#### Test 55613145c131883_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
--------- beginning of /dev/log/system
I/ActivityManager(  905): Waited long enough for: ServiceRecord{43521f98 u0 com.htc.htclocationservice/.AutoSettingService}
V/LightsService(  905): setLight #0: color=#3d
V/LightsService(  905): setLight #0: color=#39
V/LightsService(  905): setLight #0: color=#33
V/LightsService(  905): setLight #0: color=#2c
V/LightsService(  905): setLight #0: color=#25
E/cutils-trace( 4484): Error opening trace file: No such file or directory (2)
V/LightsService(  905): setLight #0: color=#1f
V/LightsService(  905): setLight #0: color=#18
V/LightsService(  905): setLight #0: color=#14
D/CustomizationManager( 4484): ====startRecUseTime====
D/htc.customization.log.level( 4484):  is 
W/CustomizationLogLevel( 4484): Level value is invalid, use default level 2
D/CustomizationManager( 4484):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4484): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4484): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4484): Parsing tag category name = system
I/CustomizationCIDLoader( 4484): Parsing tag category name = application
I/CustomizationCIDLoader( 4484): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4484): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4484): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4484): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4484): Parsing tag category name = Settings
D/CustomizationManager( 4484):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4484):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4484): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4484): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4484): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4484): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4484
D/PMS     (  905): acquireHCC(42459740): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42411f70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1112130848
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fff110
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  905): acquireWL(41fa6750): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4496 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4496): Binding Chromium to main looper Looper (main, tid 1) {41abf730}
I/LibraryLoader( 4496): Expected native library version number "",actual native library version number ""
I/chromium( 4496): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4496): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42349300:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4496): 1101880864: getState(). Returning 12
D/PMS     (  905): acquireWL(424f1590): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(4247b9c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(4247b9c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4496): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4496): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4496): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4496): Local Branch: 
I/Adreno-EGL( 4496): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4496): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4496):                  aa63bbd948f41d15fc72f585e
W/chromium( 4496): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4496): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4496): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4496): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4496): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4496): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4496): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4496): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4496): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4496): CordovaWebView is running on device made by: HTC
,W/AwContents( 4496): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1272
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +256ms
W/ResourceType( 4496): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4496): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b074d0, mServedView=org.apache.cordova.engine.SystemWebView{41acd138 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  905): Enable input method client, pid=4496
W/AwContents( 4496): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(41fa6750): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4496): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4496): JniHelper::setJavaVM(0x41596048), pthread_self() = 1662392952
,D/JX-Cordova( 4496): jxcore cordova android initializing
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 11.584MB for 95956-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 11.664MB for 143930-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 11.779MB for 215890-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 11.954MB for 323830-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 12.226MB for 485740-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 13.226MB for 1092904-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 14.100MB for 1639352-byte allocation
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 15.452MB for 2459024-byte allocation
,I/SensorManager(  905): mEventCount = 1200
,I/dalvikvm-heap( 4496): Grow heap (frag case) to 17.478MB for 3688532-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(42459740): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42411f70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
W/jxcore-log( 4496): Initializing JXcore engine
W/jxcore-log( 4496): JXcore engine is ready
,W/jxcore-log( 4496): Starting JXcore engine
,W/jxcore-log( 4496): Platform android
W/jxcore-log( 4496): 
,W/jxcore-log( 4496): Process ARCH arm
W/jxcore-log( 4496): 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/jxcore-log( 4496): JXcore Cordova bridge is ready!
I/jxcore-log( 4496): 
,W/jxcore-log( 4496): JXcore engine is started
,I/chromium( 4496): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4496): Toggling radios to true
I/jxcore-log( 4496): 
,D/BluetoothAdapter( 4496): enable(): BT is already enabled..!
,D/WifiManager( 4496): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1174
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiManager( 4496): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4496): reconnect: Base Package Name=com.test.thalitest, uid=10389
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): TDLS: Tear down peers
,I/wpa_supplicant( 1159): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4496): Radios toggled
I/jxcore-log( 4496): 
,I/jxcore-log( 4496): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4496): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4496, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1159): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1159): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1159): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  905): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1159): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb793bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): interfaceStatusCh,anged wlan0, false
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0,
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42944b68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): Fast associate: Old scan results
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  905): releaseWL(424f1590): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=21361 mDataStallAlarmIntent=PendingIntent{42447ef8: PendingIntentRecord{41f17630 android broadcastIntent}}
,D/WifiNative-wlan0(  905):    returned true
,D/WISPrService( 3855): >>>>>WISPrService start isConnected = false<<<<<
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
D/UsbnetStateTracker(  905): isAvailable+-
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WISPrService( 3855): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3855): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3855): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
,D/ConnectivityService(  905): resetConnections(wlan0, 3)
,V/NativeCrypto( 1371): Read error: ssl=0x63fe3468: I/O error during system call, Connection timed out
D/libc    (  364): [NET] entry_id:3   entry:0xb83eb8e0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb83f0190  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb83f0348  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb83f0428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb83f0090  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb83f04f0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb83ebfe8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,V/NativeCrypto( 1371): SSL shutdown failed: ssl=0x63fe3468: I/O error during system call, Broken pipe
D/PMS     (  905): acquireWL(42499bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,I//system/bin/ip(  364): RTNETLINK answers: No such process
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/PMS     (  905): acquireWL(42622990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/PMS     (  905): releaseWL(42499bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0,
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/PMS     (  905): releaseWL(42622990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
I/NetworkMonitor( 3913): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3913/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4305/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(42e92120): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4305/10100)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2740/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4550 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4550): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4550): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4550): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE,
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
W/SystemClassLoaderAdder( 4550): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 4550): Preparing secondary program dexes.
V/DexLibLoader( 4550): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4550): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4550): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4550): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4550): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,D/PMS     (  905): releaseWL(42e92120): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/DexLibLoader( 4550): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4550): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4550): Dex already copied
D/OdexVerifier( 4550): Odex verification is skipped.
V/DexLibLoader( 4550): Creating class loader
V/DexLibLoader( 4550): Finished creating class loader
V/DexLibLoader( 4550): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4550): Dex already copied
D/OdexVerifier( 4550): Odex verification is skipped.
V/DexLibLoader( 4550): Creating class loader
V/DexLibLoader( 4550): Finished creating class loader
V/DexLibLoader( 4550): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4550): Dex already copied
D/OdexVerifier( 4550): Odex verification is skipped.
V/DexLibLoader( 4550): Creating class loader
V/DexLibLoader( 4550): Finished creating class loader
V/DexLibLoader( 4550): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4550): Dex already copied
D/OdexVerifier( 4550): Odex verification is skipped.
V/DexLibLoader( 4550): Creating class loader
V/DexLibLoader( 4550): Finished creating class loader
V/DexLibLoader( 4550): Verifying classes from secondary dexes.
D/DexLibLoader( 4550): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4550): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4550): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1159): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1159): Add randomness: count=11 entropy=4
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
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
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
I/wpa_supplicant( 1159): selected network = 1
D/wpa_supplicant( 1159): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb793d4e8  current_ssid=0x0
D/wpa_supplicant( 1159): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1159): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1159): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1159): check if in concurrent case
I/wpa_supplicant( 1159): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-,wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1159): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1159): RSN: PMKSA cache search - network_ctx=0xb793d4e8 try_opportunistic=0
D/wpa_supplicant( 1159): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1159): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1159): nl80211: Set mode ifindex 22 iftype 2 (STATION),
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1159): nl80211: Unsubscribe mgmt frames handle 0xb793c718 (mode change)
D/wpa_supplicant( 1159): nl80211: Subscribe to mgmt frames with non-AP handle 0xb793c718
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718,
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Register frame type=0xd0 nl_handle=0xb793c718
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1159): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1159):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1159):   * freq=2412
D/wpa_supplicant( 1159):   * Auth Type 0,
D/wpa_supplicant( 1159):   * WPA Versions 0x2
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1159): nl80211: Connect request send successfully
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=,
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000105581167
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000105581185
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-85
I/wpa_supplicant( 1159): tsf=0000000105581189
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-90
I/wpa_supplicant( 1159): tsf=0000000105581193
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000105581181
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 105581167, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 105581185, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2452, timestamp: 105581189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 105581193, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 105581181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4550): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1159): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1159): nl80211: Connect event
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1159): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1159): Add randomness: count=12 entropy=5
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
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): Get randomness: len=32 entropy=6
D/Tethering(  905): [isWifi] getHotspotEnabled: false
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
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false,
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb793c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1159):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1159): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f90b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1159):    broadcast key
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1159): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1159): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1159): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1159): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1159): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1159): set send_ind_to_ndc = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1159): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1159): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1159): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1159): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1159): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1159): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1159): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1159): EAPOL authentication completed successfully
I/wpa_supplicant( 1159): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 79
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1159): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1159): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1159): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): [isWifi] getHotspotEnabled: false
E/FbInjectorInitializer( 4550): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WISPrService( 3855): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3855): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
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
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4366fad0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
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
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424f9bd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424f9bd0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4550): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4550): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4550): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4550): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4165
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4165:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4577 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): Util - no network available!
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/MobileConnectivityChangeReceiver( 4577): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4577): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4577): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4577): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  905): killProcessQuiet, pid=4274
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/fb4a(:<default>):UserScope( 4550): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4550): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4601 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 4274:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10079)
I/ActivityManager(  905): Recipient 4165
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10079)
I/ActivityManager(  905): Recipient 4274
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4550): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4627 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4305
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4305:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4305
,E/dalvikvm( 4550): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4550): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4550): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4550): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4550): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4550): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4550): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4550): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4550): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4550): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4550): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4550): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4550): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4550): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4550): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4550): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4550): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4550): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4627): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4550): Grow heap (frag case) to 9.921MB for 39954-byte allocation
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4550): Grow heap (frag case) to 9.998MB for 79892-byte allocation
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1159): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  905): releaseWL(4366fad0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4550): Grow heap (frag case) to 10.077MB for 84664-byte allocation
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1159): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1159): wlan0: Background scan every 600 seconds
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=21363 delay=15s
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  905): WAN detection
,D/WISPrService( 3855): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4550): Grow heap (frag case) to 10.094MB for 28144-byte allocation
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42447c58
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(431cd670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10079)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
V/WebViewChromiumFactoryProvider( 4627): Binding Chromium to main looper Looper (main, tid 1) {41ac4198}
I/LibraryLoader( 4627): Expected native library version number "",actual native library version number ""
I/chromium( 4627): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4627): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(43686e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43849f28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,E/AudioManagerAndroid( 4627): BLUETOOTH permission is missing!
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452773805898 min interval config: 0 actual interval: 46875
D/PMS     (  905): releaseWL(43686e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(44151c90): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(4318a178): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  905): releaseWL(431cd670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4318a178): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinService( 2178): Checking schedule, now: 1452773852784 next: 1452773835863
,I/CheckinService( 2178): active receiver: enabled
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2178, uid=10029, userID:0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/Adreno-EGL( 4627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4627): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4627): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4627): Local Branch: 
I/Adreno-EGL( 4627): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4627): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4627):                  aa63bbd948f41d15fc72f585e
,I/CheckinService( 2178): Preparing to send checkin request
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
I/EventLogService( 2178): Accumulating logs since 1452773801250
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,I/NSApplication( 4627): Starting up...
,I/dalvikvm-heap( 4550): Grow heap (frag case) to 10.282MB for 75760-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4377bc08 u0 ReceiverList{4377bae8 4550 com.facebook.katana/10027/u0 remote:4366cd90}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4377bc08 u0 ReceiverList{4377bae8 4550 com.facebook.katana/10027/u0 remote:4366cd90}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c71fc0 u0 ReceiverList{43860798 4550 com.facebook.katana/10027/u0 remote:440cb510}}
,D/Process (  905): killProcessQuiet, pid=4328
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
I/ActivityManager(  905): Killing 4328:com.htc.backup/1000 (adj 15): empty #17
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4328
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/wpa_supplicant( 1159): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1159): EAPOL: disable timer tick
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(441475a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): releaseWL(441475a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4680 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a1ce0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a1ce0, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bfe7f8
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@426004d8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/dalvikvm( 4680): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4550): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/dalvikvm( 4680): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4680): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4680): install
,I/MultiDex( 4680): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/MultiDex( 4680): loading existing secondary dex files
,I/MultiDex( 4680): load found 3 secondary dex files
,I/MultiDex( 4680): install done
,W/dalvikvm( 4680): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4680): VFY: unable to resolve instance field 36
,W/dalvikvm( 4680): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4680): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4680): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 2178): Restart initialization of location
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,W/dalvikvm( 4680): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4680): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1225): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1371): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1371): Proximity feature is not enabled.
,W/dalvikvm( 4680): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4680): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4680): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4680): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4680): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  905): acquireWL(4253ccf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4253ccf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 316ms
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/NativeLibraryUtils( 4680): Install completed successfully. count=14 extracted=0
D/WVCdm   (  371): PrepareKeyRequest: nonce=1443445633
,I/InputMethodManagerService(  905): Disable input method client, pid=4496
,D/NfcService( 1257): applyRouting -2
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  905): acquireWL(423463e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  905): acquireWL(422ce150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4204e830)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): releaseWL(423463e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  905): n_update end
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(422ce150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2740): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1257): applyRouting - 0
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/NfcService( 1257): applyRouting -2
,D/MtpService( 2740): [MTP][onReceive]-
D/TetherSettings( 3855): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3855): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3855): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3855): Cust_ConnectToPC   : spcsc>false
D/        ( 3855): Cust_ConnectToPC   : IPT>true
D/        ( 3855): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3855): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3855): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3855): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3855): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3855): onReceive:android.intent.action.USER_PRESENT
D/PMS     (  905): acquireWL(425d5580): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  905): releaseWL(425d5580): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/ContextImpl( 3855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/SmartNS_PSService( 3855): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3855): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3855):  defaultType:0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=21364 delay=15s
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/ClockThread( 1114): stop update clock
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): BG scan when screen On
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): Match BG scan, scan!
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4709 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  905): updateScreenOn: false
,W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(42944b68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  905): acquireWL(42bb7d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4709 1000 null
D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
,D/PMS     (  905): acquireWL(43ffc460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42bb7d90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/PMS     (  905): releaseWL(43ffc460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(4264ac08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/NetworkMonitor( 3913): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3913/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3954/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4577/10079)
,D/SmartSyncUtils( 4709): getMobilePolicyEnabled, result = true
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(430d1118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(4264ac08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false,
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOn: 1452773853789
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOn: 1452773853789
W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Process (  905): killProcessQuiet, pid=4292
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): acquireWL(4241c598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4680/10029)
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Killing 4292:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/PMS     (  905): releaseWL(4241c598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(430d1118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  905): Recipient 4292
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bfe7f8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bfe7f8, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@426004d8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2740/10021)
D/PMN     (  905): goingToSleep
,E/ExternalAccountType( 1346): Unsupported attribute readOnly
D/PMS     (  905): acquireWL(4321b710): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=21364 mDataStallAlarmIntent=PendingIntent{421bf568: PendingIntentRecord{41f17630 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
D/PMS     (  905): acquireWL(4384fad8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4577): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4577): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3626/10160)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452773805898 min interval config: 0 actual interval: 48011
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/PMS     (  905): acquireWL(43eee990): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43eee990): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4709): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,D/WVCdm   (  371): PrepareKeyRequest: nonce=812948174
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4680): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4680): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4680): Local Branch: 
I/Adreno-EGL( 4680): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4680): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits,
I/Adreno-EGL( 4680):                  aa63bbd948f41d15fc72f585e
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,I/Adreno-EGL( 4680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4680): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4680): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4680): Local Branch: 
I/Adreno-EGL( 4680): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4680): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4680):                  aa63bbd948f41d15fc72f585e
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/Adreno-EGL( 4680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4680): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4680): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4680): Local Branch: 
I/Adreno-EGL( 4680): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4680): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4680):                  aa63bbd948f41d15fc72f585e
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{42358df8 u0 com.test.thalitest/.MainActivity t2}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-60 , oldRssi= -200
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426004d8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426004d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426004d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426004d8
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4261c260 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4261c260 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/PMS     (  905): acquireWL(4361a348): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): releaseWL(4361a348): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(436f0708): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOff
D/PMS     (  905): releaseWL(436f0708): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Settings( 4680): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2178): [NET] getaddrinfo-, 1
,D/libc    ( 2178): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4b18 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,W/fb4a(:<default>):UserScope( 4550): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4550): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4384fad8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4550): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4550/10027)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =176e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/wpa_supplicant( 1159): nl80211: Event message available,
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
,I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
,I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=13 entropy=0
D/wpa_supplicant( 1159): Add randomness: count=14 entropy=1
D/wpa_supplicant( 1159): Add randomness: count=15 entropy=2
,D/wpa_supplicant( 1159): Add randomness: count=16 entropy=3
D/wpa_supplicant( 1159): Add randomness: count=17 entropy=4
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
,I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431,
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=18 entropy=5
,D/wpa_supplicant( 1159): Add randomness: count=19 entropy=6
D/wpa_supplicant( 1159): Add randomness: count=20 entropy=7
D/wpa_supplicant( 1159): Add randomness: count=21 entropy=8
D/wpa_supplicant( 1159): Add randomness: count=22 entropy=9
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1159): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 189
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2,
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2178): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000109449749
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000109449779
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-85
I/wpa_supplicant( 1159): tsf=0000000109449788
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
,I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-90
I/wpa_supplicant( 1159): tsf=0000000109449797
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000109449769
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 109449749, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 109449779, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2452, timestamp: 109449788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 109449797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 109449769, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiP2pService(  905): InactiveState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@43c4c888 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-13ms what=147462 obj=android.net.wifi.StateChangeResult@43c4c888 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-14ms what=147462 obj=android.net.wifi.StateChangeResult@43c4c888 target=com.android.internal.util.StateMachine$SmHandler }
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2178): [NET] getaddrinfo-,err=8
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(44151c90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
,D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2178): [NET] getaddrinfo-,err=8,
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8,
,I/CheckinTask( 2178): Sending checkin request (12207 bytes)
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=12 [24][3][0]
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,I/CheckinTask( 2178): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2178): Checking schedule, now: 1452773856389 next: 1453296793379
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
I/CheckinService( 2178): Checking schedule, now: 1452773856410 next: 1453296793379
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,D/CheckinService( 2178): Recording last checkin time for package unspecified as 1452773856416
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(43849f28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/PMS     (  905): acquireWL(4375b960): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1371): [NET] getaddrinfo-, 1
D/libc    ( 1371): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e08e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 138
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1371): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/PMS     (  905): acquireWL(436e1750): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/PMS     (  905): releaseWL(4375b960): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1371/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(436e1750): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(436f6ec0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1371/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1371/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(436f6ec0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4627): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4496): Test app app.js loaded
I/jxcore-log( 4496): 
,I/Choreographer( 4496): Skipped 524 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4496): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4496): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41acd138 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(4321b710): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4496): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  905): killProcessQuiet, pid=4344
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4344:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4344
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4377
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4377:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4377
D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4757 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Scheme: "mms"
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1346): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Babel   ( 4757): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4757): MmsConfig.loadMmsSettings
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4757): VFY: unable to resolve instance field 36
,W/dalvikvm( 4757): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4780 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4757, uid=10111, userID:0
,W/Settings( 4757): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4757, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4757, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4757, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4757, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4757, uid=10111, userID:0
,D/MessageFrequencyProvider( 4780): onCreate
D/PMS     (  905): acquireWL(435c57f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4757 10111 null
,V/GetPrviateResource( 4780): GetPrviateResource
,V/GetPrviateResource( 4780): GetPrviateResource
,D/MmsCustomizationProvider( 4780): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4780): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2835): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4757): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4757): MmsConfig.loadFromDatabase
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(41dbe6d8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423fdf10): PARTIAL_WAKE_LOCK  AsyncService 0x1 3626 10160 null
,D/PMS     (  905): releaseWL(423fdf10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  905): releaseWL(41dbe6d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  905): acquireWL(423095f8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4757): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4757): MmsConfig.loadFromResources
,E/Babel   ( 4757): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4757): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/PMS     (  905): releaseWL(435c57f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/PackageManager(  905): Unable to load service info ResolveInfo{425e9080 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ProviderInstaller( 4757): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Resuming delayed broadcast
D/MessageCustFlag( 4780): sense_version=6.0
D/BTAccessoryUtil( 4780): createReceiver
D/BTAccessoryUtil( 4780): registerReceiver return intent = null
D/MessageCustFlag( 4780): sku_id=99
W/SystemReader( 4780): Cannot find message_ambs_application_id, use default value instead
,D/Process (  905): killProcessQuiet, pid=4399
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Messaging( 4780): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4780): networkCode: 
D/MessageCustFlag( 4780): sku_id=99
D/MmsConfig( 4780): SIE smsPri: null
,D/MmsConfig( 4780): networkCode: 
,I/ActivityManager(  905): Killing 4399:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/HtcTelephonyCapability( 4780): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4780): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4780): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4780): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  905): Recipient 4399
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2178): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 2178): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(43b098f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43b098f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/PMS     (  905): acquireWL(42bbe178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42bbe178): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(436f6470): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436f6470): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2835): UpdateCorporaTask done [took 490 ms] updated apps [took 490 ms] 
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b51e50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2178): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2178): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(423095f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b51e50 -
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/Messaging( 4780): mNeedToUpdateDate2 start
,D/MmsConfig( 4780): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4780): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4780): 
D/MmsAsyncWorkHandler( 4780): HM tk = 20001
,D/ReportIndicatorCache( 4780): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4780): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ac6460
,I/Messaging( 4780): mccmnc> 
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/DraftCache( 4780): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4780): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4780): networkCode: 
,D/Messaging( 4780): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
D/PhoneStorageUtil( 4780): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4780): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4780): createReceiver
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4780): sense_version=6.0
,D/Jerry   ( 4780): start to preload cursor >>>>>>>
D/TelephUtils( 1244): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1244): Update uri=content://mms, match=0
,V/MmsProvider( 1244): selection=st=129 AND m_type!=134
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1244):  phoneType = -1
D/Messaging( 4780): Reset downloading state: 0
V/MmsSystemEventReceiver( 4780): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4780): mNeedToUpdateDate2: false
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,V/TransactionService( 4780): 1-Creating TransactionService
,D/AccFlag ( 1244): sku_id=99
,D/DraftCache( 4780): [DraftCache/481] rebuildCache
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1244):  phoneType = -1
V/TransactionService( 4780): onStartCommand: 1
,D/MmsSystemEventReceiver( 4780): unRegisterForConnectionStateChanges
V/TransactionService( 4780): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4780): Loading previous transactions.
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1244): device_type: 1
D/TransactionService( 4780): Force set service start id to 1
V/TransactionService( 4780): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4780): unRegisterForConnectionStateChanges
,D/Messaging( 4780): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4780): Destroying TransactionService
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/Jerry   ( 1244): URI_DRAFT
,D/TransactionService( 4780): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4780): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4780): ViewCache CreatePreload
,D/Messaging( 4780): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4780): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4780): [DraftCache/481] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4780): 
D/MmsAsyncWorkHandler( 4780): HM tk = 20002
D/Cust_MMSMS( 4780): _has_set_default_values_2=true
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1244): sku_id=99
,D/MsgPreferenceUtils( 4780): def_index: 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/AccFlag ( 1244): sku_id=99
,D/MsgPreferenceUtils( 4780): globalIndex = 1
D/MsgPreferenceUtils( 4780): phone state: true
D/MsgPreferenceUtils( 4780): sd state: false
,D/MsgPreferenceUtils( 4780): vIndex = 0
,D/Process (  905): killProcessQuiet, pid=3954
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3954:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3954
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4757): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(4315b0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{426590f0: PendingIntentRecord{4275ce00 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123349, Int=0
,D/PMS     (  905): acquireWL(436551e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4315b0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=12 [8][1][0]
I/wpa_supplicant( 1159): Change stage from stage3 to stage0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(423dff70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(423dff70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436551e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426f6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(426f6680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4355b4c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1159): Change stage from stage0 to stage3
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): acquireWL(43054b80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(435f7cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1452773869819 tag=VacuumService
,D/PMS     (  905): releaseWL(4355b4c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43054b80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44144c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(435f7cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44144c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4264bc00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(4264bc00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(440a58f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(440a58f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43a20e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43a20e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43547810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(44021ae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44021ae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4298c978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): releaseWL(43547810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43535210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(43535210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PerfProfileCollectorService( 2178): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 2178): removeStateFiles() called
,D/PerfProfileCollectorService( 2178): User is not opt-in to Usage & Diagnostics.
D/PMS     (  905): releaseWL(4298c978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42a570d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(42a570d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43885ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43885ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=23 entropy=10
D/wpa_supplicant( 1159): Add randomness: count=24 entropy=11
D/wpa_supplicant( 1159): Add randomness: count=25 entropy=12
D/wpa_supplicant( 1159): Add randomness: count=26 entropy=13
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=241,2 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=27 entropy=14
D/wpa_supplicant( 1159): Add randomness: count=28 entropy=15
D/wpa_supplicant( 1159): Add randomness: count=29 entropy=16
D/wpa_supplicant( 1159): Add randomness: count=30 entropy=17
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
,I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE,
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
,I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000126642218
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000126642256
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
,I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000126642266
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=3
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-90
I/wpa_supplicant( 1159): tsf=0000000109449797
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000126642245
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 126642218, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 126642256, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 126642266, distance: ?(cm), distanceSd: ?(cm)
,D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 109449797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 126642245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiP2pService(  905): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4387b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(4387b7d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43188688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41abda00: PendingIntentRecord{42335090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133726, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43188688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ce0800 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  905): acquireWL(43c06ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43868a98: PendingIntentRecord{42a6c150 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138197, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
,D/PMS     (  905): releaseWL(43c06ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44183e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757,
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909,
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183,
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/PMS     (  905): acquireWL(4341c088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44183e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 11430 seconds from now (1452773884919)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
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
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6582 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=37 [8][3][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4341c088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42a77bd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(42a77bd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4326a5b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1371/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/PMS     (  905): releaseWL(4326a5b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(43210ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4251c648: PendingIntentRecord{4251c530 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142953, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43412600): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(43210ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7ca3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=31 entropy=18
D/wpa_supplicant( 1159): Add randomness: count=32 entropy=19
D/wpa_supplicant( 1159): Add randomness: count=33 entropy=20
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-85
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=34 entropy=21
D/wpa_supplicant( 1159): Add randomness: count=35 entropy=22
D/wpa_supplicant( 1159): Add randomness: count=36 entropy=23
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000143842202
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000143842229
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-85
I/wpa_supplicant( 1159): tsf=0000000143842240
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=4
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000126642245
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 143842202, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 143842229, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2452, timestamp: 143842240, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 126642245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  905): killProcessQuiet, pid=4419
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4419:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4419
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(43412600): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4369d1c8 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=37 entropy=24
D/wpa_supplicant( 1159): Add randomness: count=38 entropy=25
D/wpa_supplicant( 1159): Add randomness: count=39 entropy=26
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
,I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=40 entropy=27
D/wpa_supplicant( 1159): Add randomness: count=41 entropy=28
D/wpa_supplicant( 1159): Add randomness: count=42 entropy=29
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-46
I/wpa_supplicant( 1159): tsf=0000000161183614
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000161183640
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000161183651
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 161183614, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 161183640, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 161183651, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == (3) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43219628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43219628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4433
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4433:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4433
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=43 entropy=30
D/wpa_supplicant( 1159): Add randomness: count=44 entropy=31
D/wpa_supplicant( 1159): Add randomness: count=45 entropy=32
D/wpa_supplicant( 1159): Add randomness: count=46 entropy=33
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1159): Add randomness: count=47 entropy=34
D/wpa_supplicant( 1159): Add randomness: count=48 entropy=35
D/wpa_supplicant( 1159): Add randomness: count=49 entropy=36
D/wpa_supplicant( 1159): Add randomness: count=50 entropy=37
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
,I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000178583782
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000178583820
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000178583831
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====,
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000178583808
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 178583782, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 178583820, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 178583831, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 178583808, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(42852670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42852670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(43ffe2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41abda00: PendingIntentRecord{42335090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193726, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ffe2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=51 entropy=38
D/wpa_supplicant( 1159): Add randomness: count=52 entropy=39
D/wpa_supplicant( 1159): Add randomness: count=53 entropy=40
D/wpa_supplicant( 1159): Add randomness: count=54 entropy=41
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1159): Add randomness: count=55 entropy=42
D/wpa_supplicant( 1159): Add randomness: count=56 entropy=43
D/wpa_supplicant( 1159): Add randomness: count=57 entropy=44
D/wpa_supplicant( 1159): Add randomness: count=58 entropy=45
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000195953709
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
,I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000195953745
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000195953755
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000195953734
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 195953709, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 195953745, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 195953755, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 195953734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=59 entropy=46
D/wpa_supplicant( 1159): Add randomness: count=60 entropy=47
D/wpa_supplicant( 1159): Add randomness: count=61 entropy=48
D/wpa_supplicant( 1159): Add randomness: count=62 entropy=49
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=63 entropy=50
D/wpa_supplicant( 1159): Add randomness: count=64 entropy=51
D/wpa_supplicant( 1159): Add randomness: count=65 entropy=52
D/wpa_supplicant( 1159): Add randomness: count=66 entropy=53
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
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
I/wpa_supplicant( 1159): reply (489) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000213273672
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000213273709
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000213273719
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000213273698
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
,I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 213273672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 213273709, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 213273719, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 213273698, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 4 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43634a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{43768c20: PendingIntentRecord{441a2b00 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226638, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4866 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{41ffe6e0: PendingIntentRecord{426777e8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452773958707, Int=10800000
,D/PMS     (  905): releaseWL(43634a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4866/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,D/Process (  905): killProcessQuiet, pid=4138
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4138:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4138
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4405fa10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(4405fa10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/PMS     (  905): acquireWL(43c1de20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{435c5838: PendingIntentRecord{43841350 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=227238, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{442e4160: PendingIntentRecord{441a2b00 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227571, Int=0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025188
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025624
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025746
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025749
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025757
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025766
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027090
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027102
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029909
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360031183
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/PMS     (  905): releaseWL(43c1de20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=67 entropy=54
D/wpa_supplicant( 1159): Add randomness: count=68 entropy=55
D/wpa_supplicant( 1159): Add randomness: count=69 entropy=56
D/wpa_supplicant( 1159): Add randomness: count=70 entropy=57
D/wpa_supplicant( 1159): Add randomness: count=71 entropy=58
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cm,d 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=72 entropy=59
D/wpa_supplicant( 1159): Add randomness: count=73 entropy=60
D/wpa_supplicant( 1159): Add randomness: count=74 entropy=61
D/wpa_supplicant( 1159): Add randomness: count=75 entropy=62
D/wpa_supplicant( 1159): Add randomness: count=76 entropy=63
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
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
I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000230442236
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000230442273
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000230442283
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000230442262
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000230442293
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_,supplicant( 1159): ####
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 230442236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 230442273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 230442283, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 230442262, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2437, timestamp: 230442293, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=77 entropy=64
D/wpa_supplicant( 1159): Add randomness: count=78 entropy=65
D/wpa_supplicant( 1159): Add randomness: count=79 entropy=66
D/wpa_supplicant( 1159): Add randomness: count=80 entropy=67
D/wpa_supplicant( 1159): Add randomness: count=81 entropy=68
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1159): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplic,ant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=82 entropy=69
D/wpa_supplicant( 1159): Add randomness: count=83 entropy=70
D/wpa_supplicant( 1159): Add randomness: count=84 entropy=71
D/wpa_supplicant( 1159): Add randomness: count=85 entropy=72
D/wpa_supplicant( 1159): Add randomness: count=86 entropy=73
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
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
I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000247713867
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000247713904
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000247713916
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000247713893
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000247713925
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_,supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 247713867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 247713904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 247713916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 247713893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2437, timestamp: 247713925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/PMS     (  905): acquireWL(42485618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PMS     (  905): releaseWL(42485618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42451d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41abda00: PendingIntentRecord{42335090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253725, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.640MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(42451d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=87 entropy=74
D/wpa_supplicant( 1159): Add randomness: count=88 entropy=75
D/wpa_supplicant( 1159): Add randomness: count=89 entropy=76
D/wpa_supplicant( 1159): Add randomness: count=90 entropy=77
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0,
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1159): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
I/wpa_supplicant( 1159): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1159): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=91 entropy=78
D/wpa_supplicant( 1159): Add randomness: count=92 entropy=79
D/wpa_supplicant( 1159): Add randomness: count=93 entropy=80
D/wpa_supplicant( 1159): Add randomness: count=94 entropy=81
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (632) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000264983455
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000264983482
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000264983492
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=5
I/wpa_supplicant( 1159): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000247713893
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1159): ssid=01ABC
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000264983502
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 264983455, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 264983482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2452, timestamp: 264983492, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 247713893, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2437, timestamp: 264983502, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=95 entropy=82
D/wpa_supplicant( 1159): Add randomness: count=96 entropy=83
D/wpa_supplicant( 1159): Add randomness: count=97 entropy=84
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-83
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=98 entropy=85
D/wpa_supplicant( 1159): Add randomness: count=99 entropy=86
D/wpa_supplicant( 1159): Add randomness: count=100 entropy=87
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 le,n=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (519) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
,I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000282293515
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000282293541
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-83
I/wpa_supplicant( 1159): tsf=0000000282293552
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=6
I/wpa_supplicant( 1159): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1159): freq=2437
I/wpa_supplicant( 1159): level=-92
I/wpa_supplicant( 1159): tsf=0000000264983502
I/wpa_supplicant( 1159): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=UPC Wi-Free
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 282293515, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 282293541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2452, timestamp: 282293552, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2437, timestamp: 264983502, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426760c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426760c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=101 entropy=88
D/wpa_supplicant( 1159): Add randomness: count=102 entropy=89
D/wpa_supplicant( 1159): Add randomness: count=103 entropy=90
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=104 entropy=91
D/wpa_supplicant( 1159): Add randomness: count=105 entropy=92
D/wpa_supplicant( 1159): Add randomness: count=106 entropy=93
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000299663418
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000299663445
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000299663456
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 299663418, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 299663445, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 299663456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 3 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == (3) end of scan result ==
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(435477b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435477b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(437062c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41abda00: PendingIntentRecord{42335090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=313726, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437062c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=107 entropy=94
D/wpa_supplicant( 1159): Add randomness: count=108 entropy=95
D/wpa_supplicant( 1159): Add randomness: count=109 entropy=96
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=110 entropy=97
D/wpa_supplicant( 1159): Add randomness: count=111 entropy=98
D/wpa_supplicant( 1159): Add randomness: count=112 entropy=99
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id,=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
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
,I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000317003922
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000317003948
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000317003959
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 317003922, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 317003948, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 317003959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 3 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1159): wpa_supplicant_scan enter
I/wpa_supplicant( 1159): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1159): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1159): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1159): nl80211: Event message available
,D/wpa_supplicant( 1159): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1159): nl80211: Event message available
D/wpa_supplicant( 1159): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1159): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1159): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1159): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=113 entropy=100
D/wpa_supplicant( 1159): Add randomness: count=114 entropy=101
D/wpa_supplicant( 1159): Add randomness: count=115 entropy=102
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): Selecting BSS from priority group 1
I/wpa_supplicant( 1159): Recent assoc_freq = 2412 rssi = -60
D/wpa_supplicant( 1159): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1159): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1159): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1159):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1159):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1159): Start print parameters
I/wpa_supplicant( 1159): wpa_s->wpa_state is 9
I/wpa_supplicant( 1159): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1159): isConcurrentMode() is 0
I/wpa_supplicant( 1159): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1159): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1159): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1159): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1159): wpa_s->reassociate is 0
I/wpa_supplicant( 1159): wpa_s->is_screen_on 0
I/wpa_supplicant( 1159): wpa_s->ifname wlan0
I/wpa_supplicant( 1159): End print parameters
I/wpa_supplicant( 1159): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1159): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1159): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1159): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1159): nl80211: Survey data missing
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1159): Sorted scan results
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1159): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1159): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-86
D/wpa_supplicant( 1159): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1159): Add randomness: count=116 entropy=103
D/wpa_supplicant( 1159): Add randomness: count=117 entropy=104
D/wpa_supplicant( 1159): Add randomness: count=118 entropy=105
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1159): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1159): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1159): wpa_supplicant_pick_network+
I/wpa_supplicant( 1159): clear disabled list - type=1
I/wpa_supplicant( 1159): No suitable network found
W/wpa_supplicant( 1159): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1159): State: INACTIVE -> INACTIVE
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
I/wpa_supplicant( 1159): reply (376) for get BSS: id=0
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1159): freq=5220
I/wpa_supplicant( 1159): level=-45
I/wpa_supplicant( 1159): tsf=0000000334224012
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG7005g
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=1
I/wpa_supplicant( 1159): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1159): freq=2412
I/wpa_supplicant( 1159): level=-60
I/wpa_supplicant( 1159): tsf=0000000334224038
I/wpa_supplicant( 1159): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1159): ssid=NG700
I/wpa_supplicant( 1159): ====
I/wpa_supplicant( 1159): id=2
I/wpa_supplicant( 1159): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1159): freq=2452
I/wpa_supplicant( 1159): level=-86
I/wpa_supplicant( 1159): tsf=0000000334224049
I/wpa_supplicant( 1159): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1159): ssid=Gonzos
I/wpa_supplicant( 1159): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -60, 0,
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 334224012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 334224038, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2452, timestamp: 334224049, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList,
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-60], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/jxcore-log( 4496): --= Surplus to requirements =--,
I/jxcore-log( 4496): 
I/jxcore-log( 4496): ****TEST TOOK:  ms ****
I/jxcore-log( 4496): 
,I/jxcore-log( 4496): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4496): 
,E/cutils-trace( 4891): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4891): ====startRecUseTime====
D/htc.customization.log.level( 4891):  is 
,W/CustomizationLogLevel( 4891): Level value is invalid, use default level 2
,D/CustomizationManager( 4891):  Read ACC file spent 0.095 (s)
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 4891): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4891): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4891): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4891): Parsing tag category name = system
I/CustomizationCIDLoader( 4891): Parsing tag category name = application,
I/CustomizationCIDLoader( 4891): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4891): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4891): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4891): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4891): Parsing tag category name = Settings,
D/CustomizationManager( 4891):  Read CID file spent 0.145 (s)
,D/CustomizationManager( 4891):  All configurations done spent 0.146 (s)
,W/HtcNativeFlag( 4891): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4891): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4891): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4891): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4891, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4496
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 4496:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42358df8 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4496 uid 10389
,W/PackageSettings(  905): Skipping PackageSetting{42186af8 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(438b4730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(438b4730): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1346): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  905): WIN DEATH: Window{425e3e10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2835): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/AccTypeManager( 1346): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1346): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4906 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1346): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(440461d8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(440461d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(438b54c0): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2835): UpdateCorporaTask done [took 524 ms] updated apps [took 524 ms] 
,E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4906): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4906): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4906): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4906): threadid=11: thread exiting with uncaught exception (group=0x4168ee30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
,E/AndroidRuntime( 4906): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4906): Process: com.google.android.apps.docs, PID: 4906
E/AndroidRuntime( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4906): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
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
,D/Process ( 4906): killProcess, pid=4906
,D/Process ( 4906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4925 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  905): Recipient 4906
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4906) has died.
,W/ContextImpl( 4925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4925): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4925): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4925): threadid=10: thread exiting with uncaught exception (group=0x4168ee30)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4938 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4925): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4925): Process: com.android.keychain, PID: 4925
E/AndroidRuntime( 4925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4925): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4925): killProcess, pid=4925
,D/Process ( 4925): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452774082777.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/AppTag  ( 4938): getInstance(Context context)
I/ActivityManager(  905): Recipient 4925
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4925) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4938): getInstance(Context context)
,D/AppTag  ( 4938): onCreate()
,D/PMS     (  905): acquireWL(425c4af0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3626 10160 null
,W/dalvikvm( 4100): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PMS     (  905): releaseWL(425c4af0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2178): Clearing selected account for com.test.thalitest
,D/Process (  905): killProcessQuiet, pid=4467
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4467:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  905): Recipient 4467
,D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2178): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66c80aa0
,E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca85840
,W/dalvikvm( 2178): threadid=42: thread exiting with uncaught exception (group=0x4168ee30)
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
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2178): FATAL EXCEPTION: PlayGamesAsyncThread1
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
,E/SQLiteDatabase( 2178): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2178): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2178): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2178): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2178): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2178): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2178): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2178): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2178): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2178): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2178): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2178): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
E/SQLiteOpenHelper( 2178): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2178): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2178): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2178): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2178): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2178): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2178): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2178): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2178): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2178): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2178): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2178): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2178): killProcess, pid=2178
D/Process ( 2178): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/SQLiteOpenHelper( 2178): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2178): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b51e50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
I/ActivityManager(  905): Recipient 2178
I/ActivityManager(  905): Process com.google.android.gms (pid 2178) has died.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): handleWLDeath(438b54c0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20992ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20991ms
,E/SQLiteLog( 1371): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1371): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x65f8ba10
,W/dalvikvm( 1371): threadid=1: thread exiting with uncaught exception (group=0x4168ee30)
,E/AndroidRuntime( 1371): FATAL EXCEPTION: main
E/AndroidRuntime( 1371): Process: com.google.process.gapps, PID: 1371
E/AndroidRuntime( 1371): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1371): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1371): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1371): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1371): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1371): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1371): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1371): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1371): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1371): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1371): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1371): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1371): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1371): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1371): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1371): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1371): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1371): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1371): 	... 10 more
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
,D/Process ( 1371): killProcess, pid=1371
,D/Process ( 1371): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4971 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4971): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4971 dbg=false s=true
,I/DeviceManagement( 4971): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4971): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4971): WorkflowService: Starting workflow service
I/DeviceManagement( 4971): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41af0de0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4971): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4971): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4971): PackageUpdateWorkflow: ==================================================
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Recipient 1371
W/PackageManager(  905): Unable to load service info ResolveInfo{424a0890 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/DeviceManagement( 4971): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4985 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  905): Process com.google.process.gapps (pid 1371) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30772ms
,I/DeviceManagement( 4971): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4971): SessionStateController: Checking invariants...

```
