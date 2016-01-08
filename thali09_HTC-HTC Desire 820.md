#### Test 54970261d953416_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
V/LightsService(  905): setLight #0: color=#26
V/LightsService(  905): setLight #0: color=#22
V/LightsService(  905): setLight #0: color=#1c
V/LightsService(  905): setLight #0: color=#15
V/LightsService(  905): setLight #0: color=#14
--------- beginning of /dev/log/main
E/cutils-trace( 4471): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4471): ====startRecUseTime====
D/htc.customization.log.level( 4471):  is 
W/CustomizationLogLevel( 4471): Level value is invalid, use default level 2
D/CustomizationManager( 4471):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4471): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4471): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4471): Parsing tag category name = system
I/CustomizationCIDLoader( 4471): Parsing tag category name = application
I/CustomizationCIDLoader( 4471): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4471): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4471): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4471): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4471): Parsing tag category name = Settings
D/CustomizationManager( 4471):  Read CID file spent 0.110 (s)
D/CustomizationManager( 4471):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 4471): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4471): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4471): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4471): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4471
D/PMS     (  905): acquireHCC(43c0a978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(440d71b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62d70868 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1132604984
D/PMS     (  905): acquireWL(437ba5e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420e8088
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4482 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4482): Copying FileAsset 0x5d847c88 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4482): Binding Chromium to main looper Looper (main, tid 1) {41b43d20}
I/LibraryLoader( 4482): Expected native library version number "",actual native library version number ""
I/chromium( 4482): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4482): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(43c15370): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): acquireWL(441981e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44177160:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4482): 1102429936: getState(). Returning 12
D/PMS     (  905): releaseWL(441981e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4482): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4482): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4482): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4482): Local Branch: 
I/Adreno-EGL( 4482): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4482): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4482):                  aa63bbd948f41d15fc72f585e
W/chromium( 4482): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4482): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4482): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4482): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4482): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4482): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4482): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4482): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4482): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4482): CordovaWebView is running on device made by: HTC
W/AwContents( 4482): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1269
W/ResourceType( 4482): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4482): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b8d5a0, mServedView=org.apache.cordova.engine.SystemWebView{41b53208 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Enable input method client, pid=4482
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4482): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +406ms
D/PMS     (  905): releaseWL(437ba5e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4482): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4482): JniHelper::setJavaVM(0x4161e048), pthread_self() = 1663753144
D/JX-Cordova( 4482): jxcore cordova android initializing
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 11.581MB for 95956-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 11.660MB for 143930-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 11.775MB for 215890-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 11.950MB for 323830-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 12.222MB for 485740-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 14.105MB for 1639352-byte allocation
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 15.445MB for 2459024-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4482): Grow heap (frag case) to 17.476MB for 3688532-byte allocation
W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(43c0a978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  905): releaseHCC(440d71b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4482): Initializing JXcore engine
,W/jxcore-log( 4482): JXcore engine is ready
,W/jxcore-log( 4482): Starting JXcore engine
,W/jxcore-log( 4482): Platform android
W/jxcore-log( 4482): 
,W/jxcore-log( 4482): Process ARCH arm
W/jxcore-log( 4482): 
,I/jxcore-log( 4482): JXcore Cordova bridge is ready!
I/jxcore-log( 4482): 
,W/jxcore-log( 4482): JXcore engine is started,
,I/chromium( 4482): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4482): Toggling radios to true
I/jxcore-log( 4482): 
,D/BluetoothAdapter( 4482): enable(): BT is already enabled..!
,D/WifiManager( 4482): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1235
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4482, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 6(ms)
D/WifiManager( 4482): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4482): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): TDLS: Tear down peers
I/wpa_supplicant( 1156): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4482): Radios toggled
I/jxcore-log( 4482): 
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1156): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1156): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1156): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb83febc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1156):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1156): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1156): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set suppli,cant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1156): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/PMS     (  905): acquireWL(43be7528): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): Fast associate: Old scan results
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): State: DISCONNECTED -> SCANNING
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20785 mDataStallAlarmIntent=PendingIntent{425f3888: PendingIntentRecord{426226f8 android broadcastIntent}}
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  905): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3861): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3861): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1361): Read error: ssl=0x66061cd0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x66061cd0: I/O error during system call, Broken pipe,
D/WISPrService( 3861): >>>>>WISPrService start isConnected = false<<<<<
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(436e7870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/libc    (  362): [NET] entry_id:3   entry:0xb8d2c220  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb8d2bfd8  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb8d2c2f8  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb8d2c428  removed 
,D/libc    (  362): [NET] entry_id:6   entry:0xb8d2c860  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb8d2c0e8  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb8d2c738  removed 
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3861): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  905): releaseWL(43c15370): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(42563da0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/PMS     (  905): releaseWL(42563da0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  905): releaseWL(436e7870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4533 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4335/10100)
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4335/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(440d5638): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(440d5638): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,I/MusicStore( 4533): Database version: 95
,W/ContextImpl( 4533): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4533): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4533): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4533, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4533): Registered
,I/MediaRouter( 4533): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4533/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1998/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4553 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4533): getSelectedRoute
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4533/10154)
I/NetworkMonitor( 4533): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4533, uid=10154, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ACRA    ( 4553): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  905): killProcessQuiet, pid=3898
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): acquireWL(440dc588): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(440dc588): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Killing 3898:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4553): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4553): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4553): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4553): Preparing secondary program dexes.
V/DexLibLoader( 4553): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4553): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4553): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4553): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4553): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4553): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4553): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4553): Dex already copied
D/OdexVerifier( 4553): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4553): Creating class loader
,V/DexLibLoader( 4553): Finished creating class loader
V/DexLibLoader( 4553): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4553): Dex already copied
D/OdexVerifier( 4553): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4553): Creating class loader,
V/DexLibLoader( 4553): Finished creating class loader
,V/DexLibLoader( 4553): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4553): Dex already copied
D/OdexVerifier( 4553): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4553): Creating class loader,
V/DexLibLoader( 4553): Finished creating class loader,
V/DexLibLoader( 4553): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4553): Dex already copied
D/OdexVerifier( 4553): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4553): Creating class loader,
V/DexLibLoader( 4553): Finished creating class loader
,V/DexLibLoader( 4553): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4553): DexLibLoader.ensureDexLoaded took 19 ms
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3898
,W/dalvikvm( 4553): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1156): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1156): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1156): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 3
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 1
I/wpa_supplicant( 1156): wpa_s->is_screen_on 1
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): selected network = 1
D/wpa_supplicant( 1156): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84004e8  current_ssid=0x0
D/wpa_supplicant( 1156): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1156): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1156): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1156): check if in concurrent case
,I/wpa_supplicant( 1156): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
,D/wpa_supplicant( 1156): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1156): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1156): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1156): RSN: PMKSA cache search - network_ctx=0xb84004e8 try_opportunistic=0
D/wpa_supplicant( 1156): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1156): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1156): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1156): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1156): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1156): nl80211: Unsubscribe mgmt frames handle 0xb83ff718 (mode change),
D/wpa_supplicant( 1156): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83ff718
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb83ff718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1156): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1156):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1156):   * freq=2412
D/wpa_supplicant( 1156):   * Auth Type 0
D/wpa_supplicant( 1156):   * WPA Versions 0x2
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1156): nl80211: Connect request send successfully
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1156): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (489) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000105661105
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000105661125
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-81
I/wpa_supplicant( 1156): tsf=0000000105661130
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000105661118
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105661105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 105661125, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 105661130, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 105661118, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1156): nl80211: Connect event
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1156): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1156): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1156): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1156): TDLS: Remove peers on association
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1156): EAPOL: enable timer tick
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1156): Get randomness: len=32 entropy=5
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1156): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb83ff9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1156):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1156): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa9b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1156):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1156): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1156): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1156): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1156): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1156): set send_ind_to_ndc = 0
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1156): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1156): EAPOL authentication completed successfully
I/wpa_supplicant( 1156): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  905): updateConnectedAP...,
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3861): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 3861): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 1
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(437407c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425bf150 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425bf150 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4553): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4553): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4553): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4553): Verify
,I/SensorManager(  905): mEventCount = 1050
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4553): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4553): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  905): killProcessQuiet, pid=4271
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4271:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/AutoSetting( 1328): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4589 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
D/AutoSetting( 1328): Util - no network available!
D/AutoSetting( 1328): service - onCreate()
D/AutoSetting( 1328): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  905): request 4266e480 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1328): service - mHandler: cancel location update
,D/AutoSetting( 1328): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4589): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4589): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4589): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4589): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4618 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/fb4a(:<default>):UserScope( 4553): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4553): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4589/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4589/10079)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4589/10079)
,W/fb4a(:<default>):UserScope( 4553): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  905): Recipient 4271
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4553): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4634 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4172
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4172:com.google.android.talk/u0a111 (adj 15): empty #17
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4553): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4553): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4553): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4553): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4553): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4553): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4553): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4553): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4553): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4553): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4553): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4553): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4553): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4553): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4553): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4553): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4553): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4553): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/GAV2    ( 4634): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 9.923MB for 39954-byte allocation
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(437407c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1156): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
I/ActivityManager(  905): Recipient 4172
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1156): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20787 delay=15s
,D/WISPrService( 3861): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiWatchdogStateMachine(  905): WAN detection
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 10.081MB for 84664-byte allocation
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@424ca9e8
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4634/10151)
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a6e98
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a6e98, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e05b0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4275c108
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:2
W/PMS     (  905): mWirelessDisplayManager is null
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 10.093MB for 28144-byte allocation
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=100 [1][1][0]
D/PMS     (  905): acquireWL(427346a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4589/10079)
D/wpa_supplicant( 1156): EAPOL: startWhen --> 0
D/wpa_supplicant( 1156): EAPOL: disable timer tick
D/PMS     (  905): acquireWL(43214fd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
V/WebViewChromiumFactoryProvider( 4634): Binding Chromium to main looper Looper (main, tid 1) {41b4b1e8}
I/LibraryLoader( 4634): Expected native library version number "",actual native library version number ""
I/chromium( 4634): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4634): Initializing chromium process, renderers=0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(436fdab8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1452280424398 min interval config: 0 actual interval: 47615
D/PMS     (  905): releaseWL(427346a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  905): releaseWL(43214fd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/AudioManagerAndroid( 4634): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(4411e5a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): acquireWL(4410bad8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  905): releaseWL(4410bad8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
I/CheckinService( 2176): Checking schedule, now: 1452280472034 next: 1452280454373
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2176): Preparing to send checkin request
I/EventLogService( 2176): Accumulating logs since 1452280419556
,I/Adreno-EGL( 4634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4634): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4634): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4634): Local Branch: 
I/Adreno-EGL( 4634): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4634): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4634):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/NSApplication( 4634): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4634/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4634/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I/dalvikvm-heap( 4553): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/Process (  905): killProcessQuiet, pid=4304
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3625/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3625/10160)
,I/ActivityManager(  905): Killing 4304:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Recipient 4304
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44115428 u0 ReceiverList{43973220 4553 com.facebook.katana/10027/u0 remote:437bb9f0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44115428 u0 ReceiverList{43973220 4553 com.facebook.katana/10027/u0 remote:437bb9f0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43702710 u0 ReceiverList{437026b0 4553 com.facebook.katana/10027/u0 remote:43629650}}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(432e2d98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(432e2d98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4553): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4553): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 327ms
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@428c9e88)
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/InputMethodManagerService(  905): Disable input method client, pid=4482
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(437d8340): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  905): releaseWL(437d8340): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): acquireWL(42738d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(42738d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=99
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,D/MtpService( 1998): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1998): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting - 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1328): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/PMS     (  905): acquireWL(43bc5da0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  905): releaseWL(43bc5da0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1114): stop update clock
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4695 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/TetherSettings( 3861): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3861): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3861): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3861): Cust_ConnectToPC   : spcsc>false
D/        ( 3861): Cust_ConnectToPC   : IPT>true
D/        ( 3861): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3861): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3861): hasRemovableStorageSlot: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
I/BatteryController( 1114): status:2 level:99 unsupport:false plugged:true
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20788 delay=15s
D/SmartNS_Utility( 3861): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3861): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,I/PSReceiver( 3861): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:On
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): BG scan when screen On
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): Match BG scan, scan!
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 3861): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SmartNS_PSService( 3861): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3861): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3861):  defaultType:0
,V/SRS_Proc(  369): ParamSet string: screen_state=on
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,W/dalvikvm( 4695): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4695): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4695): install
,I/MultiDex( 4695): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4695): loading existing secondary dex files
,I/MultiDex( 4695): load found 3 secondary dex files
,I/MultiDex( 4695): install done
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4709 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/dalvikvm( 4695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4695): VFY: unable to resolve instance field 36
,W/dalvikvm( 4695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,V/JNIHelp ( 4695): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PMS     (  905): acquireWL(43bce1d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(43bce1d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4360d778): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1784): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): onScreenOn: 1452280472557
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1784): onScreenOn: 1452280472557
D/PMS     (  905): releaseWL(4360d778): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4370a118): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4709 1000 null
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e05b0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e05b0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4275c108
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(43780c98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4370a118): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20788 mDataStallAlarmIntent=PendingIntent{42369d58: PendingIntentRecord{426226f8 android broadcastIntent}}
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/PMS     (  905): acquireWL(4418bbd8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/SmartSyncUtils( 4709): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4335
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ProviderInstaller( 4695): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  905): Killing 4335:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4335
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4695): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4695): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4695): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4695): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4695): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  369): PrepareKeyRequest: nonce=4099396278
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/PMS     (  905): releaseWL(43be7528): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4589/10079)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/PMS     (  905): acquireWL(43b5fa08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(43b5fa08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3978/10053)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4533/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4533): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{440d7000 u0 com.test.thalitest/.MainActivity t2}
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  369): CdmEngine::OpenSession
I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:Off
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1156): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  905): NoActiveNetworkState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/PMS     (  905): acquireWL(44138620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/PMS     (  905): releaseWL(44138620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43775bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,V/SRS_Proc(  369): ParamSet string: screen_state=off
D/PMS     (  905): releaseWL(43775bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  905): updateScreenOn: false
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
D/ContactMessageStore( 1239): Background delete complete
D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
D/SmartSyncUtils( 4709): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4709): isEpsOn(), nState = 0
D/WVCdm   (  369): PrepareKeyRequest: nonce=4246697248
D/WifiService(  905): New client listening to asynchronous messages
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4275c108
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4275c108, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4275c108, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4275c108
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275c6e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275c6e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/WearableService( 1220): callingUid 10029, callindPid: 1220
,I/WVCdm   (  369): CdmEngine::CloseSession
,E/MDM     ( 1220): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2176): Restart initialization of location
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
D/PMS     (  905): acquireWL(42440c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42440c50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4241af98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1784): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1784): onScreenOff
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
D/PMS     (  905): releaseWL(4241af98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(431228e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(431228e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1998/10021)
,D/AutoSetting( 1328): service - mHandler: cancel location update
,D/AutoSetting( 1328): service -           changes count: 0
,D/AutoSetting( 1328): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4589): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4589): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1328): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1328): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1328): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4634/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3625/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3625/10160)
,D/PMS     (  905): acquireWL(43c2d928): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1452280424398 min interval config: 0 actual interval: 49041
D/PMS     (  905): releaseWL(43c2d928): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/Settings( 4695): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4695/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =115f +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(4418bbd8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,W/fb4a(:<default>):UserScope( 4553): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4553): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1156): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1156): Add randomness: count=13 entropy=2
D/wpa_supplicant( 1156): Add randomness: count=14 entropy=3
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-5,5
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1156): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1156): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1156): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: DISCONNECTED -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (489) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000109298821
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000109298846
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000109298852
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000109298838
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 109298821, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 109298846, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 109298852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 109298838, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/WifiP2pService(  905): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4251e390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4251e390 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4251e390 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 230
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
V/ScoreHelper(  905): Only print Top 10 in ApScanList
D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4553): Called registerBroadcastReceiver twice.
,I/CheckinTask( 2176): Sending checkin request (12202 bytes)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4553/10027)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =cbd2 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,D/PMS     (  905): acquireWL(425f1f70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4533 10154 null
,W/ContextImpl( 4533): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4533, uid=10154, userID:0
,D/PMS     (  905): releaseWL(4411e5a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  905): releaseWL(425f1f70): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4533): Conditions not met for autocaching.
W/ContextImpl( 4533): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4533): Stop autocaching.
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=5 [19][1][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2176): Checking schedule, now: 1452280475253 next: 1452803412244
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,I/CheckinService( 2176): Checking schedule, now: 1452280475284 next: 1452803412244
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1452280475295
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(436fdab8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  905): acquireWL(437b6398): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =e73b +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): acquireWL(425bc1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): releaseWL(437b6398): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(425bc1c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4422d0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4422d0c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=27 [11][3][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4634): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4482): Test app app.js loaded
I/jxcore-log( 4482): 
,I/Choreographer( 4482): Skipped 521 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4482): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4482): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4482): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b53208 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(43780c98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  905): killProcessQuiet, pid=4351
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4351:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4351
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4322
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4322:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4322
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4770 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :,
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4770): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4770): MmsConfig.loadMmsSettings
,W/dalvikvm( 4770): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4770): VFY: unable to resolve instance field 36
,W/dalvikvm( 4770): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4770): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4793 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4770, uid=10111, userID:0
,D/MessageFrequencyProvider( 4793): onCreate
,V/GetPrviateResource( 4793): GetPrviateResource
,V/GetPrviateResource( 4793): GetPrviateResource
,D/MmsCustomizationProvider( 4793): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/Settings( 4770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4770, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4770, uid=10111, userID:0
,D/MmsCustomizationProvider( 4793): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4770, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4770, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4770, uid=10111, userID:0
,I/Babel   ( 4770): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4770): MmsConfig.loadFromDatabase
D/PMS     (  905): acquireWL(43706e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4770 10111 null
,E/Babel   ( 4770): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4770): MmsConfig.loadFromResources
,E/Babel   ( 4770): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4770): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
,I/ProviderInstaller( 4770): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2835): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/MessageCustFlag( 4793): sense_version=6.0
,D/BTAccessoryUtil( 4793): createReceiver
,D/BTAccessoryUtil( 4793): registerReceiver return intent = null
D/MessageCustFlag( 4793): sku_id=99
,W/SystemReader( 4793): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4793): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4793): networkCode: 
,D/MessageCustFlag( 4793): sku_id=99
,D/PMS     (  905): acquireWL(43859ea0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/MmsConfig( 4793): SIE smsPri: null
,D/MmsConfig( 4793): networkCode: 
D/HtcTelephonyCapability( 4793): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4793): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4793): getRATByHtcTelephonyCapability:1
,D/PMS     (  905): releaseWL(43859ea0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 4793): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  905): releaseWL(43706e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  905): acquireWL(434c8da0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4375
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4375:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4375
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(434c8da0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43709c68): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42b13ad8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3625 10160 null
,D/PMS     (  905): releaseWL(42b13ad8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  905): releaseWL(43709c68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43397f60): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PMS     (  905): releaseWL(43397f60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  905): acquireWL(440dea40): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440dea40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(43852468): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2835): UpdateCorporaTask done [took 675 ms] updated apps [took 675 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41bd9d10 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,W/PackageManager(  905): Unable to load service info ResolveInfo{44160810 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41bd9d10 -
,I/ActivityManager(  905): Killing 3978:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
D/Process (  905): killProcessQuiet, pid=3978
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3978
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/PMS     (  905): acquireWL(44129918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(44129918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(434135f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(434135f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(437005e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(437005e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  905): releaseWL(43852468): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4793): mNeedToUpdateDate2 start
,D/MmsConfig( 4793): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4793): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4793): 
D/MmsAsyncWorkHandler( 4793): HM tk = 20001
D/ReportIndicatorCache( 4793): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4793): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b4d500
,I/Messaging( 4793): mccmnc> 
D/DraftCache( 4793): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4793): [DraftCache/1] refresh
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsConfig( 4793): networkCode: 
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4793): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4793): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4793): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4793): createReceiver
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4793): sense_version=6.0
,D/Jerry   ( 4793): start to preload cursor >>>>>>>
,D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/Messaging( 4793): Reset downloading state: 0
V/MmsSystemEventReceiver( 4793): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4793): 1-Creating TransactionService
V/TransactionService( 4793): onStartCommand: 1
,D/MmsSystemEventReceiver( 4793): unRegisterForConnectionStateChanges
V/TransactionService( 4793): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4793): Loading previous transactions.
,D/Messaging( 4793): mNeedToUpdateDate2: false
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,D/DraftCache( 4793): [DraftCache/478] rebuildCache
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4793): ViewCache CreatePreload
,D/Messaging( 4793): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4793): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Cust_MMSMS( 4793): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4793): def_index: 0
,D/MsgPreferenceUtils( 4793): globalIndex = 1
D/MsgPreferenceUtils( 4793): phone state: true
D/MsgPreferenceUtils( 4793): sd state: false
,D/MsgPreferenceUtils( 4793): vIndex = 0
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1239): device_type: 1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1239): URI_DRAFT
D/TransactionService( 4793): Force set service start id to 1
V/TransactionService( 4793): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4793): unRegisterForConnectionStateChanges
,D/TransactionService( 4793): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4793): Destroying TransactionService
,V/TransactionService( 4793): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/DraftCache( 4793): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4793): [DraftCache/478] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4793): 
D/MmsAsyncWorkHandler( 4793): HM tk = 20002
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1239): sku_id=99
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1239): sku_id=99
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{438fbae0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4770): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(4422f9e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{44204840: PendingIntentRecord{4270e560 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123175, Int=0
,D/PMS     (  905): acquireWL(44223140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4422f9e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=16 [12][2][0]
,I/wpa_supplicant( 1156): Change stage from stage3 to stage0
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(441d2438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441d2438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44223140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44186ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(44186ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4417b478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949,
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1156): Change stage from stage0 to stage3
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(4410b958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 2176): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 2176): Failed to execute periodic sync, missing client context - aborting
D/PMS     (  905): releaseWL(4410b958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440f0768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4417b478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440ea660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
D/PMS     (  905): releaseWL(440ea660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43d35128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
D/PMS     (  905): releaseWL(43d35128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4242a328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4242a328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
D/libc    ( 1220): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =aa77 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13640
D/libc    (  362): [NET]res_nsend:resplen=45
D/libc    (  362): [NET]res_queryN: exit 3, ancount=1
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1156): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1156): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1156): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 ,level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1156): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1156): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1156): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (489) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000126362602
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000126362639
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000126362649
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000126362627
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
,W/PhenotypeConfigurator( 1220): Server returned 404
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 126362602, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 126362639, distance: ?(cm), distanceSd: ?(cm)
D/PMS     (  905): acquireWL(42558c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 126362649, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 126362627, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiManager( 1220): getScanResults enter 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=6 [16][1][0]
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiStateMachine(  905): == begin of scan result ==
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/WifiStateMachine(  905): == (4) end of scan result ==
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(440f0768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): acquireWL(424493e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42558c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4315ec00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4315ec00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42774820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(424493e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(42774820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426f66f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(426f66f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42595e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): acquireWL(426dd038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1452280491839 tag=VacuumService
,D/PMS     (  905): acquireWL(4236cda8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426dd038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42595e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4428a5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4236cda8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4428a5b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(424ef6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(424ef6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423e2960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(423e2960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43d3dfa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(43d3dfa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=99
D/PMS     (  905): runPSCheck
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4237c980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c3ff88: PendingIntentRecord{41c3ff08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=134775, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4237c980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(438bff88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{41b3bf28: PendingIntentRecord{4265b530 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138149, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  905): releaseWL(438bff88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43bb5a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/AutoSetting( 1328): service - has update message, not stop
,D/AutoSetting( 1328): service - mHandler: update timezone
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1514): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1514): service - mHandler: update timezone
D/PMS     (  905): acquireWL(42366498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1514): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1514): service - showManualTimeZoneSelector() send notification (single)
D/PMS     (  905): releaseWL(43bb5a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ed1270 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 6 3 11
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 13178 seconds from now (1452280503827)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =1792 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 221
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(42366498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4268f9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4268f9f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4427dc30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4427dc30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(423c0458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4259a178: PendingIntentRecord{425b66d8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142358, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/PMS     (  905): acquireWL(42f86a68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): releaseWL(423c0458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =592d +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1156): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1156): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1156): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1156): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (489) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000143462185
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000143462211
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000143462223
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000126362627
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 143462185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 143462211, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 143462223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 126362627, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiManager( 1220): getScanResults enter 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(42f86a68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43cc6528 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1156): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1156): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1156): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1156): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (376) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000160743814
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000160743839
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000160743850
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 160743814, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 160743839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 160743850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 3 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (3) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(436daea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436daea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=99
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:2 level:99 unsupport:false plugged:true
,D/AutoSetting( 1328): service - handleMessage() stop self
,D/AutoSetting( 1328): service - onDestroy() END
,D/AutoSetting( 1328): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4406
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4406:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4406
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4421
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4421:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4421,
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1156): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1156): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1156): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1156): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (376) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000177973871
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412,
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000177973898
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000160743850
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 177973871, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 177973898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 160743850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 3 to mScanResults
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==,
D/WifiManager( 1220): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (3) end of scan result ==
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(44117038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44117038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42696e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c3ff88: PendingIntentRecord{41c3ff08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=194775, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42696e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1156): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1156): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1156): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1156): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplican,t( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1156): Add randomness: count=51 entropy=40
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1156): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1156): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1156): Add randomness: count=54 entropy=43
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000195223609
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1,
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000195223647
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000195223657
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000195223635
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=5
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000195223666
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 195223609, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 195223647, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 195223657, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 195223635, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 195223666, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiManager( 1220): getScanResults enter 
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1156): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1156): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1156): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1156): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1156): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1156): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1156): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1156): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000212473742
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000212473781
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000212473791
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_suppl,icant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000212473770
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=5
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000212473802
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 212473742, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 212473781, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 212473791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 212473770, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 212473802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4415f668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{42191b58: PendingIntentRecord{43a67388 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227130, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4879 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{424f7998: PendingIntentRecord{42356668 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452280577874, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{4236e480: PendingIntentRecord{426c8f70 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=227141, Int=120000
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/PMS     (  905): releaseWL(4415f668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4879/10049)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024959
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025104
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025181
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025187
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025199
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026674
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026686
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029551
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360030949
,D/Process (  905): killProcessQuiet, pid=4145
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4145:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PMS     (  905): acquireWL(427c2dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{433bf540: PendingIntentRecord{43a67388 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227376, Int=0
,D/PMS     (  905): releaseWL(427c2dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ActivityManager(  905): Recipient 4145
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
,I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1156): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1156): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1156): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1156): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1156): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1156): Add randomness: count=72 entropy=61
D/wpa_supplicant( 1156): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1156): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000229552343
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000229552384
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000229552396
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000229552369
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=5
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000229552405
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 229552343, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 229552384, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 229552396, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 229552369, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 229552405, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WifiManager( 1220): getScanResults enter ,
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000),
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/PMS     (  905): acquireWL(440dbb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderNotification, total:0
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(440dbb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1114): closing low battery warning: level=100
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1600): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4709): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/TetherSettings( 3861): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3861): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3861): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3861): Cust_ConnectToPC   : spcsc>false
D/        ( 3861): Cust_ConnectToPC   : IPT>true
D/        ( 3861): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3861): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3861): Index of the first 1 = -1
W/ContextImpl( 3861): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3861): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3861): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3861): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3861): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,W/ContextImpl( 3861): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3861): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1156): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1156): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1156): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found,
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
,D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1156): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1156): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1156): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000229552343
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000246824156
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000229552396
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000246824143
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=5
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000229552405
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 229552343, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 246824156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 229552396, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 246824143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 229552405, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1,
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1220): getScanResults enter 
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43bd30c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43bd30c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4411a590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41c3ff88: PendingIntentRecord{41c3ff08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=254775, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4411a590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1156): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1156): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1156): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1156): Add randomness: count=88 entropy=77
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1156): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1156): Add randomness: count=90 entropy=79
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1156): reply (489) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000264123706
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000264123745
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000264123756
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000264123732
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 264123706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 264123745, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 264123756, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 264123732, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 4 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (4) end of scan result ==
,D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1156): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1156): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1156): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1156): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): ,send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1156): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1156): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1156): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1156): Add randomness: count=100 entropy=89
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000281434164
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000281434200
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000281434213
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supp,licant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000281434189
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=6
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000281434222
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 281434164, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  905): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 281434200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 281434213, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 281434189, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 281434222, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1156): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1156): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1156): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0,
D/wpa_supplicant( 1156): Add randomness: count=105 entropy=94
D/wpa_supplicant( 1156): Add randomness: count=106 entropy=95
D/wpa_supplicant( 1156): Add randomness: count=107 entropy=96
D/wpa_supplicant( 1156): Add randomness: count=108 entropy=97
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (636) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000298663711
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000298663742
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80,
I/wpa_supplicant( 1156): tsf=0000000298663753
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-55
I/wpa_supplicant( 1156): tsf=0000000281434189
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=6
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-93
I/wpa_supplicant( 1156): tsf=0000000298663762
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ####
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 298663711, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 298663742, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 298663753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 281434189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 298663762, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 5 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (5) end of scan result ==
D/WifiManager( 1220): getScanResults enter 
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/jxcore-log( 4482): --= Surplus to requirements =--
I/jxcore-log( 4482): 
,I/jxcore-log( 4482): ****TEST TOOK:  ms ****
I/jxcore-log( 4482): 
,I/jxcore-log( 4482): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4482): 
,E/cutils-trace( 4902): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4902): ====startRecUseTime====
D/htc.customization.log.level( 4902):  is 
,W/CustomizationLogLevel( 4902): Level value is invalid, use default level 2
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/CustomizationManager( 4902):  Read ACC file spent 0.123 (s)
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4902): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4902): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4902): Parsing tag category name = system
,I/CustomizationCIDLoader( 4902): Parsing tag category name = application
I/CustomizationCIDLoader( 4902): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4902): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4902): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4902): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4902): Parsing tag category name = Settings
D/CustomizationManager( 4902):  Read CID file spent 0.179 (s),
,D/CustomizationManager( 4902):  All configurations done spent 0.179 (s),
,W/HtcNativeFlag( 4902): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4902): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4902): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4902): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4902, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4482
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905): Killing 4482:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  905):   Force finishing activity ActivityRecord{440d7000 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x6e6d8120 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1206): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4482 uid 10389
W/PackageSettings(  905): Skipping PackageSetting{422f7310 com.example.hello/10397} due to missing metadata
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{42565bd8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/PMS     (  905): acquireWL(43c016c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(43c016c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
,W/SQLiteConnectionPool( 2176): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsRemoved
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2835): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO",
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4918 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(425a64c0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2835): UpdateCorporaTask done [took 321 ms] updated apps [took 321 ms] 
,W/PackageManager(  905): Unable to load service info ResolveInfo{42469ae8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4918): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4918): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4918): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4918): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4918): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4918): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4918): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4918): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4918): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4918): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4918): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4918): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4918): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4918): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4918): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4918): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4918): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4918): ,	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4918): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4918): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4918): ,	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4918): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4918): 	at fx.a(GellyInjectorStore.java:95)
,E/SQLiteOpenHelper( 4918): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4918): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4918): 	,at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4918): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4918): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4918): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4918): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
,E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4918): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4918): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4918): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4918): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4918): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4918): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4918): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4918): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4918): threadid=11: thread exiting with uncaught exception (group=0x41716e30),
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4918): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4918): Process: com.google.android.apps.docs, PID: 4918
E/AndroidRuntime( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4918): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4918): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4918): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4918): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4918): 	at aho.run(AbstractDatabaseInstance.java:455)
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
,E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4918): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4918): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4918): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4918): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221),
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829),
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4918): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
,E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4918): ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4918): ,	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4918): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
,E/SQLiteOpenHelper( 4918): 	,at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4918): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4918): Opened ClientFlag.db in read-only mode
D/Process ( 4918): killProcess, pid=4918
,D/Process ( 4918): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4937 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/ActivityManager(  905): Recipient 4918
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4453
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4453:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4918) has died.
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  905): Recipient 4453
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4937): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4937): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4937): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4937): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4937): threadid=10: thread exiting with uncaught exception (group=0x41716e30)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4937): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4937): Process: com.android.keychain, PID: 4937
E/AndroidRuntime( 4937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4937): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4937): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4937): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4950 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4937): killProcess, pid=4937
,D/Process ( 4937): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452280671340.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4937
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 4937) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4950): getInstance(Context context)
,D/AppTag  ( 4950): getInstance(Context context)
,D/AppTag  ( 4950): onCreate()
,D/PMS     (  905): acquireWL(436ce300): PARTIAL_WAKE_LOCK  AsyncService 0x1 3625 10160 null
,W/dalvikvm( 4105): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/PMS     (  905): releaseWL(436ce300): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656818c0
,E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e144310
,W/dalvikvm( 2176): threadid=44: thread exiting with uncaught exception (group=0x41716e30)
,E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2176): killProcess, pid=2176
,D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): handleWLDeath(425a64c0): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  905): Client connection lost with reason: 4
I/ActivityManager(  905): Recipient 2176
,I/ActivityManager(  905): Process com.google.android.gms (pid 2176) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20998ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20993ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30991ms
,E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f87380
,W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x41716e30)
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1361): FATAL EXCEPTION: main
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
,D/Process ( 1361): killProcess, pid=1361
,D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4982 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4982): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4982 dbg=false s=true
,I/DeviceManagement( 4982): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4982): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4982): WorkflowService: Starting workflow service
I/DeviceManagement( 4982): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b77f60] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4982): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4982): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4982): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4982): ModelRegistry: Loading model meta data from resources...
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Recipient 1361
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4996 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  905): Process com.google.process.gapps (pid 1361) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30840ms
I/DeviceManagement( 4982): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4982): SessionStateController: Checking invariants...
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41bd9d10 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,D/Documents( 4996): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4996): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4996): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4996): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4996): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4996): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4996): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4996): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4996): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4996): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4996): threadid=1: thread exiting with uncaught exception (group=0x41716e30)
E/AndroidRuntime( 4996): FATAL EXCEPTION: main
E/AndroidRuntime( 4996): Process: com.android.documentsui, PID: 4996
E/AndroidRuntime( 4996): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4996): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4996): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4996): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4996): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4996): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4996): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4996): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4996): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4996): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4996): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4996): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4996): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4996): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4996): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4996): 	... 10 more
,I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5010 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=4589
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  905): App crashed! Process: com.android.documentsui
I/ActivityManager(  905): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5022 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  905): Killing 4589:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,I/ActivityManager(  905): Killing 4618:com.android.chrome/u0a96 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=4618
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
,D/Process ( 4996): killProcess, pid=4996
,D/Process ( 4996): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 4589
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452280671946.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  905): Recipient 4618
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4996
,I/ActivityManager(  905): Process com.android.documentsui (pid 4996) has died.
,E/SQLiteDatabase( 4982): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4982): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4982): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4982): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4982): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4982): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4982): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4982): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4982): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/ExternalStorage( 5010): After updating volumes, found 1 active roots
E/SQLiteDatabase( 4982): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4982): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4982): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4982): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4982): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4982): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4982): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b77f60]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4982): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4982): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4982): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4982): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4982): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4982): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4982): WorkflowService: Stopping workflow service
W/dalvikvm( 5022): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 5022): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5022): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5022): install
I/MultiDex( 5022): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5022): loading existing secondary dex files
I/MultiDex( 5022): load found 3 secondary dex files
,I/MultiDex( 5022): install done

```
