#### Test 539786637913587_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  907): setLight #0: color=#3f
V/LightsService(  907): setLight #0: color=#3b
V/LightsService(  907): setLight #0: color=#31
D/PMS     (  907): acquireWL(425e7ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
--------- beginning of /dev/log/main
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=103230, Int=0
V/LightsService(  907): setLight #0: color=#2b
D/PMS     (  907): releaseWL(425e7ef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
V/LightsService(  907): setLight #0: color=#27
I/ClockThread( 1114): now=1450442820057 next=59943
V/LightsService(  907): setLight #0: color=#21
V/LightsService(  907): setLight #0: color=#1a
V/LightsService(  907): setLight #0: color=#14
,E/cutils-trace( 4490): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4490): ====startRecUseTime====
D/htc.customization.log.level( 4490):  is 
W/CustomizationLogLevel( 4490): Level value is invalid, use default level 2
D/CustomizationManager( 4490):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4490): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4490): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4490): Parsing tag category name = system
I/CustomizationCIDLoader( 4490): Parsing tag category name = application
I/CustomizationCIDLoader( 4490): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4490): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4490): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4490): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4490): Parsing tag category name = Settings
D/CustomizationManager( 4490):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4490):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4490): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4490): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4490): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4490): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4490
D/PMS     (  907): acquireHCC(4333aba0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(425e5970): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x691539c8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1114039760
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f076d8
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  907): acquireWL(4219a208): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4501 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4501): Copying FileAsset 0x5c71c680 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4501): Binding Chromium to main looper Looper (main, tid 1) {41dba3d8}
I/LibraryLoader( 4501): Expected native library version number "",actual native library version number ""
I/chromium( 4501): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4501): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(428e47d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(427ec588): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427c97f0:true
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4501): 1105002000: getState(). Returning 12
D/PMS     (  907): releaseWL(427ec588): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4501): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4501): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4501): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4501): Local Branch: 
I/Adreno-EGL( 4501): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4501): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4501):                  aa63bbd948f41d15fc72f585e
W/chromium( 4501): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4501): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4501): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4501): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4501): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4501): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4501): CordovaWebView is running on device made by: HTC
,W/AwContents( 4501): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +293ms
,W/ResourceType( 4501): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4501): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e014c0, mServedView=org.apache.cordova.engine.SystemWebView{41dc7128 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Disable input method client, pid=1269
I/InputMethodManagerService(  907): Enable input method client, pid=4501
,W/AwContents( 4501): nativeOnDraw failed; clearing to background color.
,D/PMS     (  907): releaseWL(4219a208): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/JsMessageQueue( 4501): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4501): JniHelper::setJavaVM(0x41976010), pthread_self() = 1662204504
,D/JX-Cordova( 4501): jxcore cordova android initializing
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 11.609MB for 146998-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 11.727MB for 220492-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 11.906MB for 330734-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 12.185MB for 496096-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 12.595MB for 744140-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 14.068MB for 1674304-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 15.505MB for 2511452-byte allocation
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 17.571MB for 3767174-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(4333aba0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(425e5970): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4501): Initializing JXcore engine
,W/jxcore-log( 4501): JXcore engine is ready
,W/jxcore-log( 4501): Starting JXcore engine
,W/jxcore-log( 4501): Platform android
W/jxcore-log( 4501): 
,W/jxcore-log( 4501): Process ARCH arm
W/jxcore-log( 4501): 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43e7e870 u0 com.htc.htclocationservice/.AutoSettingService}
,I/jxcore-log( 4501): JXcore Cordova bridge is ready!
I/jxcore-log( 4501): 
,W/jxcore-log( 4501): JXcore engine is started
,I/chromium( 4501): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4501): Toggling radios to true
I/jxcore-log( 4501): 
,D/BluetoothAdapter( 4501): enable(): BT is already enabled..!
,D/WifiManager( 4501): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 918
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
D/WifiService(  907): setWifiEnabled: true pid=4501, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  907): New client listening to asynchronous messages
D/WifiManager( 4501): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4501): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): TDLS: Tear down peers
I/wpa_supplicant( 1169): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4501): Radios toggled
I/jxcore-log( 4501): 
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1169): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1169): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d6fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1169): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1169): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(4433c7e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): Fast associate: Old scan results
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20020 mDataStallAlarmIntent=PendingIntent{428296a8: PendingIntentRecord{426060b0 android broadcastIntent}}
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,V/NativeCrypto( 1368): Read error: ssl=0x5ca74630: I/O error during system call, Connection timed out
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:3   entry:0xb8cdb8e0  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8ce0190  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8ce0348  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8ce0428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8ce0258  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8ce04f0  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8ce0968  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NativeCrypto( 1368): SSL shutdown failed: ssl=0x5ca74630: I/O error during system call, Broken pipe
D/PMS     (  907): acquireWL(43e91698): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): releaseWL(428e47d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(443a19b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/PMS     (  907): releaseWL(43e91698): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  907): releaseWL(443a19b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(43efd4f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43efd4f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4552 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4552): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4552): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4552): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4552): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4552): Preparing secondary program dexes.
V/DexLibLoader( 4552): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4552): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4552): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4552): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4552): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4552): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4552): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
,V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Verifying classes from secondary dexes.
,D/DexLibLoader( 4552): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4552): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1169): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1169): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1169): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1169): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1169): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 3
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 1
I/wpa_supplicant( 1169): wpa_s->is_screen_on 1
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): selected network = 1
D/wpa_supplicant( 1169): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d714e8  current_ssid=0x0
D/wp,a_supplicant( 1169): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1169): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1169): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1169): check if in concurrent case
,I/wpa_supplicant( 1169): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1169): RSN: PMKSA cache search - network_ctx=0xb8d714e8 try_opportunistic=0
D/wpa_supplicant( 1169): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1169): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1169): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1169): nl80211: Unsubscribe mgmt frames handle 0xb8d70718 (mode change)
D/wpa_supplicant( 1169): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d70718
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1169):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169):   * freq=2412
D/wpa_supplicant( 1169):   * Auth Type 0
D/wpa_supplicant( 1169):   * WPA Versions 0x2
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1169): nl80211: Connect request send successfully
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (779) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000109521389
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000109521406
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000109521410
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000109521414
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000109521401
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-89
I/wpa_supplicant( 1169): tsf=0000000109521418
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 109521389, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 109521406, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 109521410, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 109521414, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 109521401, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 109521418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4552): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1169): nl80211: Event message available
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1169): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Connect event
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1169): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Add randomness: count=13 entropy=6
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on association
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1169): EAPOL: enable timer tick
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1169): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): Get randomness: len=32 entropy=7
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d709f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  907): This record is existed, only update it...
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f24b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    broadcast key
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1169): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1169): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1169): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1169): set send_ind_to_ndc = 0
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1169): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1169): EAPOL authentication completed successfully
I/wpa_supplicant( 1169): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,E/FbInjectorInitializer( 4552): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 1
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(43f13000): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4501): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): my name is : HTC-HTC Desire 820_PT6700
I/jxcore-log( 4501): 
,W/fb4a(:<default>):StaticBindingVerifier( 4552): Verify
,I/jxcore-log( 4501): attempting to connect to test coordinator
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): check test folder
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): found test : ./testFindPeers.js
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): found test : ./testReConnect.js
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): found test : ./testSendData.js
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): Test app app.js loaded
I/jxcore-log( 4501): 
,I/jxcore-log( 4501): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4501): 
,I/Choreographer( 4501): Skipped 159 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4501): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4552): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4552): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4253
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4253:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4253
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4580 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
,D/AutoSetting( 1312): Util - no network available!
,D/AutoSetting( 1312): service - onCreate()
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/AutoSetting( 1312): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  907): request 42674d70 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1312): service - mHandler: cancel location update
D/AutoSetting( 1312): service -           changes count: 0
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4250d7b0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4250d7b0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42300148
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@4223eb18
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  907): Going to sleep due to screen timeout...
W/BatSI   (  907): Couldn't get kernel wake lock stats
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4552): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/PMS     (  907): mWirelessDisplayManager is null
D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4580): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4580): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4611 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(43f13000): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1169): Change stage from stage0 to stage3
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1169): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -63, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20022 delay=15s
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
,D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WISPrService( 3859): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4273f488
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(4342bb20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  907): acquireWL(4348ce38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43cc4c50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450442782945 min interval config: 0 actual interval: 44283
,D/PMS     (  907): releaseWL(4348ce38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 2197): Checking schedule, now: 1450442827233 next: 1450442812913
,I/CheckinService( 2197): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2197, uid=10029, userID:0
,I/CheckinService( 2197): Preparing to send checkin request
,I/EventLogService( 2197): Accumulating logs since 1450442779176
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 319ms
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1254): ScreenObserver: OFF
D/NfcService( 1254): applyRouting - 0
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1254): applyRouting -2
I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
W/ResourceType( 4501): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4501): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41dc7128 VFEDH.C. .F...... 0,0-720,1134 #64}
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43cc6140)
D/PMS     (  907): acquireWL(4293ed40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4501
D/PMS     (  907): releaseWL(4293ed40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(43fc0f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(43fc0f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
D/PMN     (  907): onScreenOn
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/MtpService( 1967): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting - 0
D/MtpService( 1967): [MTP][onReceive]-
D/NfcService( 1254): applyRouting -2
D/PMS     (  907): releaseWL(4342bb20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(43f158d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20023 delay=15s
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43f158d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,I/ClockThread( 1114): stop update clock
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/Process (  907): killProcessQuiet, pid=4286
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4647 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4286:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:On
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1169): BG scan when screen On
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): Match BG scan, scan!
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
D/WifiNative-wlan0(  907):    returned true
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4552): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4552): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4552): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4552): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4552): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,D/NetworkPolicy(  907): updateScreenOn: false
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4552): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4552): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4552): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4552): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4552): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4552): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4552): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4552): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4647): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4647): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.917MB for 39954-byte allocation
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4647): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  907): Recipient 4286
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4647): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4647): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/PMS     (  907): acquireWL(4433bed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4433bed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): acquireWL(42ea1ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1748): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): onScreenOn: 1450442827445
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1748): onScreenOn: 1450442827445
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.992MB for 79892-byte allocation
D/PMS     (  907): releaseWL(42ea1ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42300148
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42300148, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@4223eb18
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(437c0e58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.063MB for 84664-byte allocation
D/PMS     (  907): releaseWL(437c0e58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.090MB for 28144-byte allocation
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,V/WebViewChromiumFactoryProvider( 4647): Binding Chromium to main looper Looper (main, tid 1) {41dbe220}
,I/LibraryLoader( 4647): Expected native library version number "",actual native library version number ""
,I/chromium( 4647): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4647): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(43e66538): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4647): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(43783e58): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(43783e58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4647): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4647): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4647): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4647): Local Branch: 
I/Adreno-EGL( 4647): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4647): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4647):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4679 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4647): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,W/dalvikvm( 4679): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
W/dalvikvm( 4679): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4679): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4679): install
I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,I/MultiDex( 4679): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/MultiDex( 4679): loading existing secondary dex files
,I/MultiDex( 4679): load found 3 secondary dex files
,I/MultiDex( 4679): install done
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43faae08 u0 ReceiverList{43faace8 4552 com.facebook.katana/10027/u0 remote:43f40458}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43faae08 u0 ReceiverList{43faace8 4552 com.facebook.katana/10027/u0 remote:43f40458}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e98190 u0 ReceiverList{4434b398 4552 com.facebook.katana/10027/u0 remote:4434aae0}}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4701 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
W/dalvikvm( 4679): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4679): VFY: unable to resolve instance field 36
,W/dalvikvm( 4679): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4679): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,I/ProviderInstaller( 4679): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4303
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4303:com.htc.backup/1000 (adj 15): empty #17
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20023 mDataStallAlarmIntent=PendingIntent{427ce738: PendingIntentRecord{426060b0 android broadcastIntent}}
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/PMS     (  907): acquireWL(43a32c28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4701 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/PMS     (  907): acquireWL(43cc73c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/PMS     (  907): releaseWL(43a32c28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/dalvikvm( 4679): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 4679): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/SmartSyncUtils( 4701): getMobilePolicyEnabled, result = true
D/PMS     (  907): acquireWL(42bd6fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42bd6fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=4273
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/dalvikvm( 4679): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4679): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4679): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4679): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4679): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Killing 4273:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4273
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4303
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  372): CdmEngine::OpenSession
I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/NativeLibraryUtils( 4679): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=341862766
,I/WVCdm   (  372): CdmEngine::CloseSession
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1169): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1169): EAPOL: disable timer tick
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:Off
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-62 , oldRssi= -200
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1312): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3859): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3859): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3859): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3859): Cust_ConnectToPC   : spcsc>false
D/        ( 3859): Cust_ConnectToPC   : IPT>true
D/        ( 3859): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3859): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3859): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3859): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3859): onReceive:android.intent.action.USER_PRESENT
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,I/SmartNS_PSService( 3859): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3859):  defaultType:0
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): releaseWL(4433c7e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=true
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3954/10053)
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/PMS     (  907): acquireWL(43ec8838): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43e8e240): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
D/PMS     (  907): releaseWL(43e8e240): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
D/PMS     (  907): releaseWL(43ec8838): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
,E/MDM     ( 1221): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/PMS     (  907): acquireWL(4289eb50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4289eb50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationInitializer( 2197): Restart initialization of location
D/PMS     (  907): acquireWL(426914b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/AuthorizationBluetoothService( 1368): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1368): Proximity feature is not enabled.
,D/PMS     (  907): releaseWL(426914b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1748): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1748): onScreenOff
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,D/AutoSetting( 1312): service - mHandler: cancel location update
W/GCoreFlp( 1221): No location to return for getLastLocation()
D/AutoSetting( 1312): service -           changes count: 0
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  907): acquireWL(4262abc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4262abc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,W/Settings( 4679): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4701): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  907): New client listening to asynchronous messages
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4223eb18
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4223eb18, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4223eb18, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4223eb18
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42821840 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42821840 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1312): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1312): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1312): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,D/PMS     (  907): acquireWL(4274c770): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450442782945 min interval config: 0 actual interval: 45476
D/PMS     (  907): releaseWL(4274c770): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4679/10029)
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3373698755
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17,
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43cc73c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2197): [NET] getaddrinfo-, 1
,D/libc    ( 2197): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a285 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,I/jxcore-log( 4501): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4501): 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=14 entropy=0
D/wpa_supplicant( 1169): Add randomness: count=15 entropy=1
D/wpa_supplicant( 1169): Add randomness: count=16 entropy=2
D/wpa_supplicant( 1169): Add randomness: count=17 entropy=3
D/wpa_supplicant( 1169): Add randomness: count=18 entropy=4
D/wpa_supplicant( 1169): Add randomness: count=19 entropy=5
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -62
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplica,nt( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=20 entropy=6
D/wpa_supplicant( 1169): Add randomness: count=21 entropy=7
D/wpa_supplicant( 1169): Add randomness: count=22 entropy=8
D/wpa_supplicant( 1169): Add randomness: count=23 entropy=9
D/wpa_supplicant( 1169): Add randomness: count=24 entropy=10
D/wpa_supplicant( 1169): Add randomness: count=25 entropy=11
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
,W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4433d758 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (779) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000112815337
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-62
I/wpa_supplicant( 1169): tsf=0000000112815360
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-85,
I/wpa_supplicant( 1169): tsf=0000000112815367
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000112815372
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000112815353
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-89
I/wpa_supplicant( 1169): tsf=0000000112815378
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 64
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2197): [NET] getaddrinfo_proxy-, success
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4433d758 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-7ms what=147462 obj=android.net.wifi.StateChangeResult@4433d758 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -62, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 112815337, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 112815360, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 112815367, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 112815372, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 112815353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 112815378, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-62], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2197): Sending checkin request (12198 bytes)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4552): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =35de +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=15 [20][3][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,I/CheckinTask( 2197): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2197): Checking schedule, now: 1450442830427 next: 1450965767421
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,I/CheckinService( 2197): Checking schedule, now: 1450442830456 next: 1450965767421
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,D/CheckinService( 2197): Recording last checkin time for package unspecified as 1450442830463
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43cc4c50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/PMS     (  907): acquireWL(43fafe30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =44a2 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 298
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,D/PMS     (  907): releaseWL(43e66538): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  907): acquireWL(4292a0b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/PMS     (  907): releaseWL(43fafe30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(4292a0b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(428f86b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(428f86b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=18 [11][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4501): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4501): threadid=1: thread exiting with uncaught exception (group=0x41987e30)
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4501): FATAL EXCEPTION: main
E/AndroidRuntime( 4501): Process: com.test.thalitest, PID: 4501
E/AndroidRuntime( 4501): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4501): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4501): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4501): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4501): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4501): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4501): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4501): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4501): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4501): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4501): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4501): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4501): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4501): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4501): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4501): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4501): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  907): killProcessQuiet, pid=4327
,I/ActivityManager(  907): Killing 4327:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4501): killProcess, pid=4501
D/Process ( 4501): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  907): Recipient 4327
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4501 uid 10389
,E/JavaBinder( 1206): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  907): Recipient 4501
I/WindowState(  907): WIN DEATH: Window{4333ad08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.test.thalitest (pid 4501) has died.
,I/GAV2    ( 4647): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4766 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms",
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/dalvikvm( 4766): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4766): VFY: unable to resolve instance field 36
W/dalvikvm( 4766): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,V/JNIHelp ( 4766): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 4766): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4766): MmsConfig.loadMmsSettings
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4790 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4766, uid=10111, userID:0
,W/Settings( 4766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4766, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4766, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4766, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4766, uid=10111, userID:0
,D/MessageFrequencyProvider( 4790): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4766, uid=10111, userID:0
,V/GetPrviateResource( 4790): GetPrviateResource
,V/GetPrviateResource( 4790): GetPrviateResource
,D/MmsCustomizationProvider( 4790): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  907): acquireWL(43dd59e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4766 10111 null
,I/ProviderInstaller( 4766): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1312): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1312): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  907): Resuming delayed broadcast
D/MmsCustomizationProvider( 4790): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4766): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4766): MmsConfig.loadFromDatabase
,I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(429b8a18): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4766): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4766): MmsConfig.loadFromResources
,E/Babel   ( 4766): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4766): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/PMS     (  907): releaseWL(43dd59e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  907): killProcessQuiet, pid=4382
,I/ActivityManager(  907): Killing 4382:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/MessageCustFlag( 4790): sense_version=6.0
,D/BTAccessoryUtil( 4790): createReceiver
,D/BTAccessoryUtil( 4790): registerReceiver return intent = null
D/MessageCustFlag( 4790): sku_id=99
,W/SystemReader( 4790): Cannot find message_ambs_application_id, use default value instead
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4382
,D/Messaging( 4790): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4790): networkCode: 
D/MessageCustFlag( 4790): sku_id=99
,D/MmsConfig( 4790): SIE smsPri: null
,D/MmsConfig( 4790): networkCode: 
,D/HtcTelephonyCapability( 4790): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4790): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4790): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4790): Cannot find qct_8960_interface, use default value instead,
,D/PMS     (  907): releaseWL(429b8a18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42e98800): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  907): releaseWL(42e98800): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,W/PackageManager(  907): Unable to load service info ResolveInfo{43ed1c78 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  907): acquireWL(4433c1e0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(434e85f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3686 10160 null
,D/PMS     (  907): releaseWL(434e85f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): releaseWL(4433c1e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): acquireWL(43ed0498): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43ed0498): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast,
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): acquireWL(42cb6af0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  907): releaseWL(42cb6af0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(437aeab8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2197): Null package name or gms related package.  Ignoreing.
D/PMS     (  907): releaseWL(437aeab8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43e84a58): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2197): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 714 ms] updated apps [took 714 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,D/AutoSetting( 1487): service - handleMessage() stop self
,D/AutoSetting( 1487): service - onDestroy() END
,D/AutoSetting( 1487): service - handleMessage() quit looper
D/Process (  907): killProcessQuiet, pid=4409
,I/ActivityManager(  907): Killing 4409:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4409
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/Icing   ( 2197): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 -
,I/Icing   ( 2197): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(43e84a58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/Messaging( 4790): mNeedToUpdateDate2 start
,D/MmsConfig( 4790): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4790): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4790): 
D/MmsAsyncWorkHandler( 4790): HM tk = 20001
D/ReportIndicatorCache( 4790): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4790): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41dc0820
,I/Messaging( 4790): mccmnc> 
D/DraftCache( 4790): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4790): [DraftCache/1] refresh
,D/MmsConfig( 4790): networkCode: 
,D/Messaging( 4790): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4790): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4790): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/MessageCustFlag( 4790): sense_version=6.0
,D/PhoneStorageUtil( 4790): createReceiver
,D/Jerry   ( 4790): start to preload cursor >>>>>>>
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
V/MmsProvider( 1242): Update uri=content://mms, match=0
,V/MmsProvider( 1242): selection=st=129 AND m_type!=134
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Messaging( 4790): mNeedToUpdateDate2: false
,D/Messaging( 4790): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4790): TransactionService is going to be woken up.
,D/LocationProviderProxy(  907): applying state to connected service
,V/TransactionService( 4790): 1-Creating TransactionService
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): sku_id=99
D/PMS     (  907): acquireWL(4379bf20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4379bf20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/DraftCache( 4790): [DraftCache/484] rebuildCache
D/LocationProviderProxy(  907): applying state to connected service
V/TransactionService( 4790): onStartCommand: 1
D/MmsSystemEventReceiver( 4790): unRegisterForConnectionStateChanges
V/TransactionService( 4790): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4790): Loading previous transactions.
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1242):  phoneType = -1
D/PMS     (  907): acquireWL(43e479a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1242): device_type: 1
D/PMS     (  907): releaseWL(43e479a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1242): URI_DRAFT
,D/TransactionService( 4790): Force set service start id to 1
,V/TransactionService( 4790): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4790): unRegisterForConnectionStateChanges
,V/TransactionService( 4790): Destroying TransactionService
,D/PMS     (  907): acquireWL(43a0e588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/TransactionService( 4790): stopSelfResult: true, mLastHandledServiceId: 1
D/DraftCache( 4790): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4790): [DraftCache/484] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4790): 
D/MmsAsyncWorkHandler( 4790): HM tk = 20002
D/Messaging( 4790): ViewCache CreatePreload
,D/Messaging( 4790): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4790): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PMS     (  907): releaseWL(43a0e588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/Cust_MMSMS( 4790): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4790): def_index: 0
,D/MsgPreferenceUtils( 4790): globalIndex = 1
,D/MsgPreferenceUtils( 4790): phone state: true
,D/MsgPreferenceUtils( 4790): sd state: false
,D/MsgPreferenceUtils( 4790): vIndex = 0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): sku_id=99
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4790): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1242): sku_id=99
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42c26a88 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4766): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=3954
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3954:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3954
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=26 entropy=12
D/wpa_supplicant( 1169): Add randomness: count=27 entropy=13
D/wpa_supplicant( 1169): Add randomness: count=28 entropy=14
D/wpa_supplicant( 1169): Add randomness: count=29 entropy=15
D/wpa_supplicant( 1169): Add randomness: count=30 entropy=16
D/wpa_supplicant( 1169): Add randomness: count=31 entropy=17
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1,169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=32 entropy=18
D/wpa_supplicant( 1169): Add randomness: count=33 entropy=19
D/wpa_supplicant( 1169): Add randomness: count=34 entropy=20
D/wpa_supplicant( 1169): Add randomness: count=35 entropy=21
D/wpa_supplicant( 1169): Add randomness: count=36 entropy=22
D/wpa_supplicant( 1169): Add randomness: count=37 entropy=23
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (779) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000129983685
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000129983746
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-86
I/wpa_supplicant( 1169): tsf=0000000129983803
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000129983764
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000129983725
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000112815378
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 129983685, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 129983746, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2427, timestamp: 129983803, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 129983764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 129983725, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 112815378, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43804328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43804328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(437ade60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{420ebb00: PendingIntentRecord{4295bc58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=132492, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{4274c920: PendingIntentRecord{42cb21a0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141548, Int=0
,D/PMS     (  907): acquireWL(437add70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,V/AlarmManager(  907): sending alarm PendingIntent{41dda040: PendingIntentRecord{41ec2978 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141601, Int=0
,D/PMS     (  907): acquireWL(43789250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43789250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437add70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43781988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43781988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43759e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): acquireWL(43636c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1312): service - has update message, not stop
,D/AutoSetting( 1312): service - mHandler: update timezone
,D/PMS     (  907): acquireWL(425c7408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1450442858556 tag=VacuumService
,D/PMS     (  907): releaseWL(43759e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4290f2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(4290f2c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425c7408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(428632f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43636c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(428632f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42928738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(42928738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427b55d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(427b55d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/PMS     (  907): acquireWL(428f2bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bc99 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1487): service - onCreate()
D/PMS     (  907): releaseWL(437ade60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/PMS     (  907): acquireWL(4275f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
V/NotificationService(  907): batLight: Full, plugged
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1487): service - mHandler: update timezone
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1487): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1487): service - showManualTimeZoneSelector() send notification (single)
D/PMS     (  907): releaseWL(4275f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{42061960 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 11 3 11
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): releaseWL(428f2bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=38 entropy=24
D/wpa_supplicant( 1169): Add randomness: count=39 entropy=25
D/wpa_supplicant( 1169): Add randomness: count=40 entropy=26
D/wpa_supplicant( 1169): Add randomness: count=41 entropy=27
D/wpa_supplicant( 1169): Add randomness: count=42 entropy=28
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( ,1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=43 entropy=29
D/wpa_supplicant( 1169): Add randomness: count=44 entropy=30
D/wpa_supplicant( 1169): Add randomness: count=45 entropy=31
D/wpa_supplicant( 1169): Add randomness: count=46 entropy=32
D/wpa_supplicant( 1169): Add randomness: count=47 entropy=33
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (779) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000147133305
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000147133331
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-85
I/wpa_supplicant( 1169): tsf=0000000129983803
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000147133353
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=4
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
,I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000129983725
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000112815378
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 147133305, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 147133331, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 129983803, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 147133353, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 129983725, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 112815378, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43dba078 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43fb1078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43fb1078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=48 entropy=34
D/wpa_supplicant( 1169): Add randomness: count=49 entropy=35
D/wpa_supplicant( 1169): Add randomness: count=50 entropy=36
D/wpa_supplicant( 1169): Add randomness: count=51 entropy=37
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): ,[NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=52 entropy=38
D/wpa_supplicant( 1169): Add randomness: count=53 entropy=39
D/wpa_supplicant( 1169): Add randomness: count=54 entropy=40
D/wpa_supplicant( 1169): Add randomness: count=55 entropy=41
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
,I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000164544979
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000164545005
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-85
I/wpa_supplicant( 1169): tsf=0000000164545016
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=3
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000147133353
,I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000112815378
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 164544979, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 164545005, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 164545016, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 147133353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 112815378, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43e58170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43e58170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1312): service - handleMessage() stop self
,D/AutoSetting( 1312): service - handleMessage() quit looper
,D/AutoSetting( 1312): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4430
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4430:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4430
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1487): service - handleMessage() stop self
,D/AutoSetting( 1487): service - onDestroy() END
,D/AutoSetting( 1487): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4444,
,I/ActivityManager(  907): Killing 4444:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4444
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=56 entropy=42
D/wpa_supplicant( 1169): Add randomness: count=57 entropy=43
D/wpa_supplicant( 1169): Add randomness: count=58 entropy=44
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=59 entropy=45
D/wpa_supplicant( 1169): Add randomness: count=60 entropy=46
D/wpa_supplicant( 1169): Add randomness: count=61 entropy=47
D/wp,a_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (523) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000181995416
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====,
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000181995446
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-84
I/wpa_supplicant( 1169): tsf=0000000164545016
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=5
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000112815378
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 181995416, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 181995446, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 164545016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 112815378, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(428e93c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PMS     (  907): releaseWL(428e93c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43fb1d18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4272c938: PendingIntentRecord{4295bc58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192512, Int=0
,D/PMS     (  907): releaseWL(43fb1d18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(439e4328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=6 [32][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4363bab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(439e4328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4363bab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4454afb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(4454afb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4296ecf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(44351598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4296ecf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 13403 seconds from now (1450442909944)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b6a4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299,
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(44351598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43800840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43800840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43fb96a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43fb96a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=62 entropy=48
D/wpa_supplicant( 1169): Add randomness: count=63 entropy=49
D/wpa_supplicant( 1169): Add randomness: count=64 entropy=50
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1169): Add randomness: count=65 entropy=51
,D/wpa_supplicant( 1169): Add randomness: count=66 entropy=52
D/wpa_supplicant( 1169): Add randomness: count=67 entropy=53
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000199132471
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000199132499
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-84
I/wpa_supplicant( 1169): tsf=0000000164545016
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 199132471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 199132499, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 164545016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=68 entropy=54
D/wpa_supplicant( 1169): Add randomness: count=69 entropy=55
D/wpa_supplicant( 1169): Add randomness: count=70 entropy=56
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=71 entropy=57
D/wpa_supplicant( 1169): Add randomness: count=72 entropy=58
D/wpa_supplicant( 1169): Add randomness: count=73 entropy=59
D/wp,a_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000216585044
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000216585071
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000164545016
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 216585044, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 216585071, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 164545016, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/PMS     (  907): acquireWL(43f2cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f2cb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43f19730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43f19730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42996970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{426437a8: PendingIntentRecord{43cb3e58 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231014, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4875 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4273d1a0: PendingIntentRecord{4268fc18 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450442928606, Int=10800000
,D/PMS     (  907): releaseWL(42996970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  907): acquireWL(4433d448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{44392dd8: PendingIntentRecord{43cb3e58 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231068, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4263fb50: PendingIntentRecord{43959b48 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231074, Int=120000
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(4433d448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4875/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/Process (  907): killProcessQuiet, pid=4124
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4124:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4124
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=74 entropy=60
D/wpa_supplicant( 1169): Add randomness: count=75 entropy=61
D/wpa_supplicant( 1169): Add randomness: count=76 entropy=62
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=77 entropy=63
D/wpa_supplicant( 1169): Add randomness: count=78 entropy=64
D/wpa_supplicant( 1169): Add randomness: count=79 entropy=65
D/wp,a_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000233993985
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000233994025
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000233994046
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 233993985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 233994025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 233994046, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1,
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results,
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=80 entropy=66,
D/wpa_supplicant( 1169): Add randomness: count=81 entropy=67
D/wpa_supplicant( 1169): Add randomness: count=82 entropy=68
D/wpa_supplicant( 1169): Add randomness: count=83 entropy=69
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...,
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
,I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=84 entropy=70
D/wpa_supplicant( 1169): Add randomness: count=85 entropy=71
D/wpa_supplicant( 1169): Add randomness: count=86 entropy=72
D/wpa_supplicant( 1169): Add randomness: count=87 entropy=73
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (489) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000251428216
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000251428254
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-78
I/wpa_supplicant( 1169): tsf=0000000233994046
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000251428242
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 251428216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 251428254, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 233994046, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 251428242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/PMS     (  907): acquireWL(422bd7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(422bd7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available,
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48,
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=88 entropy=74
D/wpa_supplicant( 1169): Add randomness: count=89 entropy=75
D/wpa_supplicant( 1169): Add randomness: count=90 entropy=76
D/wpa_supplicant( 1169): Add randomness: count=91 entropy=77
D/wpa_supplicant( 1169): Add randomness: count=92 entropy=78
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
,D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=93 entropy=79
D/wpa_supplicant( 1169): Add randomness: count=94 entropy=80
D/wpa_supplicant( 1169): Add randomness: count=95 entropy=81,
D/wpa_supplicant( 1169): Add randomness: count=96 entropy=82
D/wpa_supplicant( 1169): Add randomness: count=97 entropy=83
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (632) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000268855280
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000268855316,
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-78
I/wpa_supplicant( 1169): tsf=0000000268855326
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000268855305
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000268855336
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 268855280, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 268855316, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 268855326, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 268855305, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 268855336, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42f37978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=283232, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42f37978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=98 entropy=84
D/wpa_supplicant( 1169): Add randomness: count=99 entropy=85
D/wpa_supplicant( 1169): Add randomness: count=100 entropy=86
D/wpa_supplicant( 1169): Add randomness: count=101 entropy=87
D/wpa_supplicant( 1169): Add randomness: count=102 entropy=88
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 116,9): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=103 entropy=89
D/wpa_supplicant( 1169): Add randomness: count=104 entropy=90
D/wpa_supplicant( 1169): Add randomness: count=105 entropy=91
D/wpa_supplicant( 1169): Add randomness: count=106 entropy=92
D/wpa_supplicant( 1169): Add randomness: count=107 entropy=93
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (632) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000286295008
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000286295045
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-79
I/wpa_supplicant( 1169): tsf=0000000286295055
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000286295034
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000286295064
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 286295008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 286295045, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 286295055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 286295034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 286295064, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43951b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43951b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=108 entropy=94
D/wpa_supplicant( 1169): Add randomness: count=109 entropy=95
D/wpa_supplicant( 1169): Add randomness: count=110 entropy=96
D/wpa_supplicant( 1169): Add randomness: count=111 entropy=97
D/wpa_supplicant( 1169): Add randomness: count=112 entropy=98
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1169): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1,169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=113 entropy=99
D/wpa_supplicant( 1169): Add randomness: count=114 entropy=100
D/wpa_supplicant( 1169): Add randomness: count=115 entropy=101
D/wpa_supplicant( 1169): Add randomness: count=116 entropy=102
D/wpa_supplicant( 1169): Add randomness: count=117 entropy=103
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (632) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-48
I/wpa_supplicant( 1169): tsf=0000000303752202
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000303752239
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-82
I/wpa_supplicant( 1169): tsf=0000000303752249
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000303752228
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000303752258
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 303752202, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 303752239, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 303752249, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 303752228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 303752258, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1,
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==,
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43ef3fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ef3fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=118 entropy=104
D/wpa_supplicant( 1169): Add randomness: count=119 entropy=105
D/wpa_supplicant( 1169): Add randomness: count=120 entropy=106
D/wpa_supplicant( 1169): Add randomness: count=121 entropy=107
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/,wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=122 entropy=108
D/wpa_supplicant( 1169): Add randomness: count=123 entropy=109
D/wpa_supplicant( 1169): Add randomness: count=124 entropy=110
D/wpa_supplicant( 1169): Add randomness: count=125 entropy=111
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (632) for get BSS: id=0,
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000303752202
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000321235318
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-79
I/wpa_supplicant( 1169): tsf=0000000321235331
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=6
I/wpa_supplicant( 1169): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000303752228
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1169): ssid=01ABC
I/wpa_supplicant( 1169): ====
,I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000321235340
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 303752202, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0,
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 321235318, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 321235331, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -63, frequency: 2412, timestamp: 303752228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 321235340, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==,
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=126 entropy=112
D/wpa_supplicant( 1169): Add randomness: count=127 entropy=113
D/wpa_supplicant( 1169): Add randomness: count=128 entropy=114
,D/wpa_supplicant( 1169): Add randomness: count=129 entropy=115
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
,I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
,I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=130 entropy=116
D/wpa_supplicant( 1169): Add randomness: count=131 entropy=117
D/wpa_supplicant( 1169): Add randomness: count=132 entropy=118
D/wpa_supplicant( 1169): Add randomness: count=133 entropy=119
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (519) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000338668741
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000338668775
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000338668788
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000338668801
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
,I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 338668741, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 338668775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 338668788, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 338668801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43b6d690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b6d690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(43efc108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43efc108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=134 entropy=120
D/wpa_supplicant( 1169): Add randomness: count=135 entropy=121
D/wpa_supplicant( 1169): Add randomness: count=136 entropy=122
D/wpa_supplicant( 1169): Add randomness: count=137 entropy=123
D/wpa_supplicant( 1169): Add randomness: count=138 entropy=124
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_su,pplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=139 entropy=125
D/wpa_supplicant( 1169): Add randomness: count=140 entropy=126
D/wpa_supplicant( 1169): Add randomness: count=141 entropy=127
D/wpa_supplicant( 1169): Add randomness: count=142 entropy=128
D/wpa_supplicant( 1169): Add randomness: count=143 entropy=129
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000356135055
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000356135081
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000356135092
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
,I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000356135101
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000356135111
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 356135055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 356135081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 356135092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 356135101, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 356135111, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(44390a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44390a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=144 entropy=130
D/wpa_supplicant( 1169): Add randomness: count=145 entropy=131
D/wpa_supplicant( 1169): Add randomness: count=146 entropy=132
D/wpa_supplicant( 1169): Add randomness: count=147 entropy=133
D/wpa_supplicant( 1169): Add randomness: count=148 entropy=134
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_su,pplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=149 entropy=135
D/wpa_supplicant( 1169): Add randomness: count=150 entropy=136
D/wpa_supplicant( 1169): Add randomness: count=151 entropy=137
D/wpa_supplicant( 1169): Add randomness: count=152 entropy=138
D/wpa_supplicant( 1169): Add randomness: count=153 entropy=139
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000373617352
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000373617378
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000373617389
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000373617398
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000373617410
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 373617352, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 373617378, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 373617389, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 373617398, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 373617410, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=154 entropy=140
D/wpa_supplicant( 1169): Add randomness: count=155 entropy=141
D/wpa_supplicant( 1169): Add randomness: count=156 entropy=142
D/wpa_supplicant( 1169): Add randomness: count=157 entropy=143
D/wpa_supplicant( 1169): Add randomness: count=158 entropy=144
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_su,pplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=159 entropy=145
D/wpa_supplicant( 1169): Add randomness: count=160 entropy=146
D/wpa_supplicant( 1169): Add randomness: count=161 entropy=147
D/wpa_supplicant( 1169): Add randomness: count=162 entropy=148
D/wpa_supplicant( 1169): Add randomness: count=163 entropy=149
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
,I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000373617352
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000391065458
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2,
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000391065469
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000391065478
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000391065488
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 373617352, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 391065458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 391065469, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 391065478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 391065488, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  907): acquireWL(42f49650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=403230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42f49650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
,I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63,
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=164 entropy=150
D/wpa_supplicant( 1169): Add randomness: count=165 entropy=151
,D/wpa_supplicant( 1169): Add randomness: count=166 entropy=152
D/wpa_supplicant( 1169): Add randomness: count=167 entropy=153
D/wpa_supplicant( 1169): Add randomness: count=168 entropy=154
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431,
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
,I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=169 entropy=155
D/wpa_supplicant( 1169): Add randomness: count=170 entropy=156
D/wpa_supplicant( 1169): Add randomness: count=171 entropy=157
,D/wpa_supplicant( 1169): Add randomness: count=172 entropy=158
D/wpa_supplicant( 1169): Add randomness: count=173 entropy=159
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000408253218
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000408253257
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-79
I/wpa_supplicant( 1169): tsf=0000000408253277
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000408253295
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000408253313
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 408253218, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 408253257, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 408253277, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 408253295, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 408253313, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(431854a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431854a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=174 entropy=160
D/wpa_supplicant( 1169): Add randomness: count=175 entropy=161
D/wpa_supplicant( 1169): Add randomness: count=176 entropy=162
D/wpa_supplicant( 1169): Add randomness: count=177 entropy=163
D/wpa_supplicant( 1169): Add randomness: count=178 entropy=164
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_su,pplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
I/wpa_supplicant( 1169): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
D/wpa_supplicant( 1169): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=179 entropy=165
D/wpa_supplicant( 1169): Add randomness: count=180 entropy=166
D/wpa_supplicant( 1169): Add randomness: count=181 entropy=167
D/wpa_supplicant( 1169): Add randomness: count=182 entropy=168
D/wpa_supplicant( 1169): Add randomness: count=183 entropy=169
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0,
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000425715168
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000425715195
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000425715205
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000425715214
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000425715224
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 425715168, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 425715195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 425715205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 425715214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 425715224, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4454d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4454d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=184 entropy=170
D/wpa_supplicant( 1169): Add randomness: count=185 entropy=171
D/wpa_supplicant( 1169): Add randomness: count=186 entropy=172
D/wpa_supplicant( 1169): Add randomness: count=187 entropy=173
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): Sorted scan results
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_su,pplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=188 entropy=174
D/wpa_supplicant( 1169): Add randomness: count=189 entropy=175
D/wpa_supplicant( 1169): Add randomness: count=190 entropy=176
D/wpa_supplicant( 1169): Add randomness: count=191 entropy=177
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (666) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000443145710
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000443145749
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_su,pplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-80
I/wpa_supplicant( 1169): tsf=0000000443145768
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000425715214
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=8
I/wpa_supplicant( 1169): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-91
I/wpa_supplicant( 1169): tsf=0000000425715224
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=UPC5999698
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 443145710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 443145749, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 443145768, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 425715214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 425715224, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=192 entropy=178
D/wpa_supplicant( 1169): Add randomness: count=193 entropy=179
D/wpa_supplicant( 1169): Add randomness: count=194 entropy=180
D/wpa_supplicant( 1169): Add randomness: count=195 entropy=181
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
I/,wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=196 entropy=182
D/wpa_supplicant( 1169): Add randomness: count=197 entropy=183
D/wpa_supplicant( 1169): Add randomness: count=198 entropy=184
D/wpa_supplicant( 1169): Add randomness: count=199 entropy=185
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (519) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000460619426
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000460619455
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-84
I/wpa_supplicant( 1169): tsf=0000000460619465
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos,
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000425715214
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 460619426, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 460619455, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 460619465, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 425715214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(432dfa28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000},
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463231, Int=0,
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(432dfa28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(431d6750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431d6750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
I/wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=200 entropy=186
D/wpa_supplicant( 1169): Add randomness: count=201 entropy=187
D/wpa_supplicant( 1169): Add randomness: count=202 entropy=188
D/wpa_supplicant( 1169): Add randomness: count=203 entropy=189
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1169): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
I/,wpa_supplicant( 1169): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 1169): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=204 entropy=190
D/wpa_supplicant( 1169): Add randomness: count=205 entropy=191
D/wpa_supplicant( 1169): Add randomness: count=206 entropy=192
D/wpa_supplicant( 1169): Add randomness: count=207 entropy=193
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (519) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000478035337
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000478035366
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-84
I/wpa_supplicant( 1169): tsf=0000000478035379
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000425715214
I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 478035337, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 478035366, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 478035379, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 425715214, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  907): acquireWL(4269e788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4269e788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=208 entropy=194
D/wpa_supplicant( 1169): Add randomness: count=209 entropy=195
D/wpa_supplicant( 1169): Add randomness: count=210 entropy=196
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=211 entropy=197
D/wpa_supplicant( 1169): Add randomness: count=212 entropy=198
D/wpa_supplicant( 1169): Add randomness: count=213 entro,py=199
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (519) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000495501100
,I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000495501128
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000495501139
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=7
I/wpa_supplicant( 1169): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1169): freq=2462
I/wpa_supplicant( 1169): level=-90
I/wpa_supplicant( 1169): tsf=0000000425715214
,I/wpa_supplicant( 1169): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=UPC Wi-Free
I/wpa_supplicant( 1169): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 495501100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 495501128, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 495501139, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 425715214, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=214 entropy=200
D/wpa_supplicant( 1169): Add randomness: count=215 entropy=201
D/wpa_supplicant( 1169): Add randomness: count=216 entropy=202
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 2412 rssi = -63
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 9
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1169): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=217 entropy=203
D/wpa_supplicant( 1169): Add randomness: count=218 entropy=204
D/wpa_supplicant( 1169): Add randomness: count=219 entro,py=205
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000512894869
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000512894898
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000512894911
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 512894869, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 512894898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 512894911, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Disconnect event
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1169): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,I/wpa_supplicant( 1169): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1169): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d6fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1169): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
,D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20024 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0,
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(426f1cc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1368): Read error: ssl=0x661d7b90: I/O error during system call, Connection timed out
D/libc    (  365): [NET] entry_id:4   entry:0xb8ce02d8  removed 
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(4273fb60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  365): [NET] entry_id:3   entry:0xb8ce00f8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8ce0428  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8ce04e0  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8ce01a8  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,V/NativeCrypto( 1368): SSL shutdown failed: ssl=0x661d7b90: I/O error during system call, Broken pipe
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:3
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(427eb060): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1368/10029)
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1169): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  907):    returned true
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  907): releaseWL(4273fb60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/PMS     (  907): releaseWL(427eb060): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): acquireWL(42e8ade0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=523231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42e8ade0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/PMS     (  907): acquireWL(43a41bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(43a41bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
,D/AutoSetting( 1312): Util - no network available!
,D/AutoSetting( 1312): service - onCreate()
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/AutoSetting( 1312): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  907): request 42674d70 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1312): service - mHandler: cancel location update
,D/AutoSetting( 1312): service -           changes count: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/iu.Environment( 2197): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2197): num queued entries: 0
,I/iu.UploadsManager( 2197): num updated entries: 0
,I/iu.SyncManager( 2197): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=220 entropy=206
D/wpa_supplicant( 1169): Add randomness: count=221 entropy=207
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): No APs found - clear blacklist and try again
E/wpa_supplicant( 1169): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1169): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1169): p2p0: Updating scan results from sibling
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=222 entropy=208
D/wpa_supplicant( 1169): Add randomness: count=223 entropy=209
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:,d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): clear disabled list - type=1
I/wpa_supplicant( 1169): No suitable network found
W/wpa_supplicant( 1169): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1169): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000524952968
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000512894898
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000524953008
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 524952968, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 512894898, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 524953008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1169): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  907):    returned true
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=224 entropy=210
D/wpa_supplicant( 1169): Add randomness: count=225 entropy=211
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 3
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): selected network = 1
D/wpa_supplicant( 1169): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d714e8  current_ssid=0x0
D/wpa_supplicant( 1169): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1169): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1169): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1169): check if in concurrent case
,I/wpa_supplicant( 1169): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1169): RSN: PMKSA cache search - network_ctx=0xb8d714e8 try_opportunistic=0
D/wpa_supplicant( 1169): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1169): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1169): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1169): nl80211: Unsubscribe mgmt frames handle 0xb8d70718 (mode change)
D/wpa_supplicant( 1169): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d70718
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1169):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169):   * freq=2412
D/wpa_supplicant( 1169):   * Auth Type 0
,D/wpa_supplicant( 1169):   * WPA Versions 0x2
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1169): nl80211: Connect request send successfully
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1169): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000530871898
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
,I/wpa_supplicant( 1169): tsf=0000000530871923
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2427
I/wpa_supplicant( 1169): level=-81
I/wpa_supplicant( 1169): tsf=0000000524953008
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 530871898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 530871923, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 524953008, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43f94100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43f94100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Connect event
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1169): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1169): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  907): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  907): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  907): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
D/WifiStateMachine(  907): Enter handleAssociateRejectEvent
,D/WifiStateMachine(  907): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
,D/WifiStateMachine(  907): Exit handleAssociateRejectEvent
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1169): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=226 entropy=212
D/wpa_supplicant( 1169): Add randomness: count=227 entropy=213
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1169): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1169):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1169): No APs found - clear blacklist and try again
E/wpa_supplicant( 1169): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1169): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-63
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 3
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): selected network = 1
D/wpa_supplicant( 1169): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d714e8  current_ssid=0x0
D/wpa_supplicant( 1169): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1169): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1169): TDLS: TDLS is allowed in the target ,BSS
I/wpa_supplicant( 1169): check if in concurrent case
,I/wpa_supplicant( 1169): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1169): RSN: PMKSA cache search - network_ctx=0xb8d714e8 try_opportunistic=0
D/wpa_supplicant( 1169): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1169): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1169): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1169): nl80211: Unsubscribe mgmt frames handle 0xb8d70718 (mode change)
D/wpa_supplicant( 1169): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d70718
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1169):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169):   * freq=2412
D/wpa_supplicant( 1169):   * Auth Type 0
D/wpa_supplicant( 1169):   * WPA Versions 0x2
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1169): nl80211: Connect request send successfully
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (238) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000535122418
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000535122443
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 535122418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 535122443, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Connect event
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1169): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Add randomness: count=228 entropy=214
,I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on association
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1169): EAPOL: enable timer tick
,D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1169): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): Get randomness: len=32 entropy=215
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  907): Associated
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d709f0 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f24b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1169): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1169): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 1169): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1169): set send_ind_to_ndc = 0
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1169): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1169): EAPOL authentication completed successfully
I/wpa_supplicant( 1169): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false,
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 1
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1169): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/PMS     (  907): acquireWL(43efdaf0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(43efdaf0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -63, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1169): Change stage from stage0 to stage3
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4273f488
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1169): EAPOL: startWhen --> 0
D/wpa_supplicant( 1169): EAPOL: disable timer tick
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(43794ad8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/PMS     (  907): acquireWL(433c0c50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450442830463 min interval config: 0 actual interval: 422924
,D/PMS     (  907): acquireWL(43e65be0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(433c0c50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checking schedule, now: 1450443253394 next: 1450442860421
,I/CheckinService( 2197): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2197, uid=10029, userID:0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/CheckinService( 2197): Preparing to send checkin request
,I/EventLogService( 2197): Accumulating logs since 1450442827263
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
D/PMS     (  907): releaseWL(43794ad8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=906461010
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4679): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4679/10029)
,D/PMS     (  907): releaseWL(426f1cc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/PMS     (  907): acquireWL(443870e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42e86f80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1703974438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/PMS     (  907): releaseWL(42e86f80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(443870e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1169): Change stage from stage3 to stage1
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1312): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1312): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1312): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  372): CdmEngine::CloseSession
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450442830463 min interval config: 0 actual interval: 424002
D/PMS     (  907): acquireWL(42cf63d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42cf63d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,I/iu.Environment( 2197): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
I/iu.UploadsManager( 2197): num queued entries: 0
I/iu.UploadsManager( 2197): num updated entries: 0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,I/iu.SyncManager( 2197): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/PMS     (  907): acquireWL(42995790): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6b08 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
V/NativeCrypto( 2197): SSL shutdown failed: ssl=0x6ea13408: I/O error during system call, Connection timed out
D/libc    ( 2197): [NET] getaddrinfo-, 1
D/libc    ( 2197): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2197): SSL shutdown failed: ssl=0x65ff5cc8: I/O error during system call, Connection timed out
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a37e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 106,
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 94
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2197): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2197): Sending checkin request (12201 bytes)
,D/PMS     (  907): acquireWL(43941e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/PMS     (  907): releaseWL(42995790): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43941e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43e46de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43e46de8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=32 [31][10][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43e0e370 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6587 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=50 [6][3][0]
,I/wpa_supplicant( 1169): Change stage from stage1 to stage3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,I/CheckinTask( 2197): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2197): Checking schedule, now: 1450443256521 next: 1450966193516
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,I/CheckinService( 2197): Checking schedule, now: 1450443256551 next: 1450966193516
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/CheckinService( 2197): Recording last checkin time for package unspecified as 1450443256559
,D/PMS     (  907): releaseWL(43e65be0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/PMS     (  907): acquireWL(42919e70): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4766 10111 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/dalvikvm-heap( 1269): Grow heap (frag case) to 12.696MB for 53840-byte allocation
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
D/PMS     (  907): releaseWL(42919e70): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/[PluginManager]RegisterService( 1312): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1312): handle notify Blinkfeed plugin client changed
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  907): acquireWL(4398e7e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3686 10160 null
,D/PMS     (  907): acquireWL(43a7c188): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): releaseWL(4398e7e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2197): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2197): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{43b8d300 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 527 ms] updated apps [took 527 ms] 
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(43dd5878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43dd5878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(435ebe50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(435ebe50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432df9a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432df9a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Icing   ( 2197): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,I/Icing   ( 2197): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(43a7c188): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 -
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,D/PMS     (  907): acquireWL(428fa0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): releaseWL(428fa0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Disconnect event
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1169): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
I/wpa_supplicant( 1169): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1169): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d6fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1169): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplic,ant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  907):    returned true
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20025 mDataStallAlarmIntent=null
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(4272e0e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '72 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 72 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '74 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 74 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1368): Read error: ssl=0x66189db0: I/O error during system call, Connection timed out
D/libc    (  365): [NET] entry_id:1   entry:0xb8ce4f68  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8cdb8f0  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8ce0550  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
,V/NativeCrypto( 1368): SSL shutdown failed: ssl=0x66189db0: I/O error during system call, Broken pipe
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  907): acquireWL(41eb2d50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  907): acquireWL(4207f858): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1368/10029)
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1169): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  907): releaseWL(41eb2d50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/PMS     (  907): releaseWL(4207f858): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
V/Tethering(  907): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  907): acquireWL(42863810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(42863810): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:2
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1312): Util - no network available!
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1312): service - mHandler: cancel location update
,D/AutoSetting( 1312): service -           changes count: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/iu.Environment( 2197): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2197): num queued entries: 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
I/iu.UploadsManager( 2197): num updated entries: 0
,I/iu.SyncManager( 2197): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1169): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1169): Failed to initiate AP scan
,I/wpa_supplicant( 1169): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-66
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=229 entropy=183
D/wpa_supplicant( 1169): Add randomness: count=230 entropy=184
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1169): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1169):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1169): No APs found - clear blacklist and try again
E/wpa_supplicant( 1169): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1169): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1169): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-66
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 3
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 0
I/wpa_supplicant( 1169): wpa_s->is_screen_on 0
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): selected network = 1
D/wpa_supplicant( 1169): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d714e8  current_ssid=0x0
D/wpa_supplicant( 1169): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1169): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1169): TDLS: TDLS i,s allowed in the target BSS
I/wpa_supplicant( 1169): check if in concurrent case
I/wpa_supplicant( 1169): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1169): RSN: PMKSA cache search - network_ctx=0xb8d714e8 try_opportunistic=0
D/wpa_supplicant( 1169): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1169): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1169): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1169): nl80211: Unsubscribe mgmt frames handle 0xb8d70718 (mode change)
D/wpa_supplicant( 1169): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d70718
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8d70718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1169):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169):   * freq=2412
D/wpa_supplicant( 1169):   * Auth Type 0
D/wpa_supplicant( 1169):   * WPA Versions 0x2
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1169): nl80211: Connect request send successfully
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00,:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1169): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  907):    returned false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (238) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000560851628
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-66
I/wpa_supplicant( 1169): tsf=0000000560851653
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 560851628, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -66, frequency: 2412, timestamp: 560851653, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): == (2) end of scan result ==
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Connect event
,D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1169): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Add randomness: count=231 entropy=185
,I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on association
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1169): EAPOL: enable timer tick
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1169): getPrivFuncNum +	
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 1169): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1169): EAPOL: disable timer tick
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state CONNECTING
,D/wpa_supplicant( 1169): EAPOL: enable timer tick
D/wpa_supplicant( 1169): EAPOL: txStart
,D/wpa_supplicant( 1169): WPA: drop TX EAPOL in non-IEEE 802.1X mode (type=1 len=0),
,I/wpa_supplicant( 1169): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): Get randomness: len=32 entropy=186
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d709f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f24b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    broadcast key
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1169): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1169): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1169): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1169): set send_ind_to_ndc = 0
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1169): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1169): EAPOL authentication completed successfully
I/wpa_supplicant( 1169): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(433c0b10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 1
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1169): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42829f80 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(433c0b10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=66 [3][2][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  907): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
E/NativeDaemonConnector.ResponseQueue(  907): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  907): Removing request: null (5)
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4273f488
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1169): Change stage from stage0 to stage3
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
E/NetdConnector(  907): NDC Command {82 resolver setifdns wlan0  192.168.1.1} took too long (798ms)
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  907): acquireWL(4275f2c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(439512e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4275f2c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(4435ade0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450443256559 min interval config: 0 actual interval: 27457
D/PMS     (  907): releaseWL(439512e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checking schedule, now: 1450443284026 next: 1450443286516
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  907): releaseWL(4435ade0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/PMS     (  907): releaseWL(4272e0e8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/AutoSetting( 1312): service - mHandler: update timezone
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1487): service - onCreate()
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1487): service - mHandler: update timezone
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1487): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1487): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41e0c8e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 1 10 3 11
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  907): NoActiveNetworkState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(43fc9878): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4361/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,I/NetworkMonitor( 4361): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43fbe688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/PMS     (  907): releaseWL(43fbe688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(43fc9878): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1967/10021)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/AutoSetting( 1312): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
,D/AutoSetting( 1312): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1312): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1312): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1312/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4647/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3686/10160)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2197): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2197): num queued entries: 0
,I/iu.UploadsManager( 2197): num updated entries: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/iu.SyncManager( 2197): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/PMS     (  907): acquireWL(43f695f8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =315 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
D/wpa_supplicant( 1169): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=232 entropy=154
D/wpa_supplicant( 1169): Add randomness: count=233 entropy=155
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1169): reply (238) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-47
I/wpa_supplicant( 1169): tsf=0000000568401406
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-63
I/wpa_supplicant( 1169): tsf=0000000568401419
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 568401406, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -63, frequency: 2412, timestamp: 568401419, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -63, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-63], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiStateMachine(  907): add 2 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (2) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 110
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/PMS     (  907): acquireWL(437bf4e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43f695f8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(437bf4e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41ebe1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(41ebe1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=35 [14][5][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =906f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{428e16b8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(42a0b980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=583231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a0b980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43746b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43746b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1169): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1169): EAPOL: disable timer tick
,D/AutoSetting( 1487): service - handleMessage() stop self
,D/AutoSetting( 1487): service - onDestroy() END
,D/AutoSetting( 1487): service - handleMessage() quit looper
,D/AutoSetting( 1312): service - mHandler: update timezone
,D/AutoSetting( 1312): service - handleMessage() stop self
,D/AutoSetting( 1312): service - handleMessage() quit looper
,D/AutoSetting( 1312): service - onDestroy() END
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1487): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1487): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1487): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1487): service - mHandler: update timezone
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1487): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1487): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1487): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{420f2798 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 4 9 3 11
,D/PMS     (  907): acquireWL(43f4da10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43f4da10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4356cf60 u0 com.htc.htclocationservice/.AutoSettingService}
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/AutoSetting( 1487): service - handleMessage() stop self
,D/AutoSetting( 1487): service - onDestroy() END
,D/AutoSetting( 1487): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4471
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4471:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4471
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4348cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=643230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4348cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43e2bf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43e2bf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(435b7b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435b7b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43f1b538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=703230, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f1b538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fc8478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43fc8478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
,D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(428bda38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(428bda38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a1f748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{42875450: PendingIntentRecord{43959b48 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531088, Int=300000
,V/AlarmManager(  907): sending alarm PendingIntent{4271c5b0: PendingIntentRecord{429cc828 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450443286516, Int=522937000
,V/AlarmManager(  907): sending alarm PendingIntent{43e28d40: PendingIntentRecord{41ebf328 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450443458255, Int=1800000
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): acquireWL(4395ceb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(439dbb88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checkin interval check for package: unspecified last checkin: 1450443256559 min interval config: 0 actual interval: 201748
D/PMS     (  907): releaseWL(4395ceb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2197): Checking schedule, now: 1450443458317 next: 1450443286516
,I/CheckinService( 2197): active receiver: enabled
D/PMS     (  907): acquireWL(42984180): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42a1f748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2197, uid=10029, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,I/CheckinService( 2197): Preparing to send checkin request
,I/EventLogService( 2197): Accumulating logs since 1450443253427
D/PMS     (  907): acquireWL(43cc2278): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42984180): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
,I/EventLogService( 2197): Aggregate from 1450443458378 (log), 1450441658205 (data)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43cc2278): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=16 [18][3][0]
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2072173078
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4679): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4679): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4679): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4679): Local Branch: 
I/Adreno-EGL( 4679): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4679): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4679):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4679/10029)
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3063888411
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2197): [NET] getaddrinfo-, 1
,D/libc    ( 2197): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =223c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2197): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
D/libc    ( 2197): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2197): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2197): Sending checkin request (12203 bytes)
,I/CheckinRequestBuilder( 2197): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2197): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2197/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=5 [20][1][0]
,I/CheckinRequestBuilder( 2197): Classify the device as Phone.
,I/CheckinTask( 2197): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2197): Checking schedule, now: 1450443460732 next: 1450966397724
,I/CheckinService( 2197): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,D/CheckinService( 2197): Recording last checkin time for package unspecified as 1450443460752
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(439dbb88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  907): acquireWL(44340928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4766 10111 null
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
,D/PMS     (  907): releaseWL(44340928): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/[PluginManager]RegisterService( 1312): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1312): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PMS     (  907): acquireWL(42e86900): PARTIAL_WAKE_LOCK  AsyncService 0x1 3686 10160 null
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PMS     (  907): acquireWL(4294a720): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42e86900): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2197): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2197): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{43f99be0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 613 ms] updated apps [took 613 ms] 
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(428120a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(428120a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(42737610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42737610): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426e67b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426e67b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,I/Icing   ( 2197): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2197): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(4294a720): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 -
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,D/PMS     (  907): acquireWL(426fa2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=763230, Int=0
,D/PMS     (  907): releaseWL(426fa2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425ddb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(425ddb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4285f9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4285f9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42330450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209d148: PendingIntentRecord{42749c40 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=792465, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): releaseWL(42330450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(426aa4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=823231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426aa4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c80330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43c80330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42908160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42908160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4379a1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=883231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4379a1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4295a5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4295a5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4223efd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4223efd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44340fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  907): releaseWL(44340fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428ef608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428ef608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4362fc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4362fc18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42941f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42722c98: PendingIntentRecord{42930150 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450443648970, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{428f6bd8: PendingIntentRecord{43923a68 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450443728345, Int=0
,W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4701): call getInstance()
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4701): MY_DEBUG = false
D/PMS     (  907): releaseWL(42941f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44392bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4701 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4701): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4701): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4701): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4701): SettingOnTime = 1450504800000, randomSettingOnTime = 1450503911000
D/SmartSyncScreenOnOffTimeReceiver( 4701): SettingOffTime = 1450490400000, randomSettingOffTime = 1450494886000
D/SmartSyncScreenOnOffTimeReceiver( 4701): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4701): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4701): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(44392bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(429a0900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(429a0900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43fb2538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43fb2538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(429c2fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1063231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1269): Grow heap (frag case) to 12.702MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(429c2fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43ec6fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ec6fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(435ec268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(435ec268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43595c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1123231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43595c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44387438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(44387438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43e471f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43e471f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(429dbfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1183231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(429dbfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(429238d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(429238d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42a3c110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/PMS     (  907): releaseWL(42a3c110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43fcc480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1243231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1269): Grow heap (frag case) to 12.702MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(43fcc480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43f06f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43f06f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4454d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4454d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4438e8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1303230, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4438e8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(443843b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(443843b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43fbe8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43fbe8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43f02dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1363230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f02dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43efe6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43efe6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43ecce40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1423231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ecce40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43ec7c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43ec7c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43e72e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(43e72e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43e2c6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{427638f8: PendingIntentRecord{42c27218 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1468789, Int=0
D/PMS     (  907): acquireWL(43e10558): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43e10558): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43e2c6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43e06ab8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1368/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1368/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024182
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024465
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024469
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024474
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024477
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025786
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025805
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028470
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030459
,D/PMS     (  907): releaseWL(43e06ab8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=39 [64][25][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43cc1c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1483231, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43cc1c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cbe470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cbe470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43a92160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43a92160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43924e18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{4209d148: PendingIntentRecord{42749c40 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1512489, Int=0
,D/PMS     (  907): releaseWL(43924e18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(41e3bc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1543230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41e3bc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4251fbb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/PMS     (  907): releaseWL(4251fbb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4272c6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4272c6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43785040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1603231, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43785040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428e0f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428e0f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43c7f680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c7f680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42310f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1663230, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42310f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42e8fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(42e8fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42069f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(42069f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42795298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1723230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42795298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43940770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43940770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42948848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(42948848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(438008e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1783230, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(438008e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42e9ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42e9ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4334b1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4334b1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(4442fd10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1843230, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  907): Prepared write state in 34ms
,D/PMS     (  907): releaseWL(4442fd10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-41-27.bin
,D/PMS     (  907): acquireWL(42674978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderNotification, total:1
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1601): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42674978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3859): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3859): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3859): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3859): Cust_ConnectToPC   : spcsc>false
D/        ( 3859): Cust_ConnectToPC   : IPT>true
,D/        ( 3859): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3859): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3859): Index of the first 1 = -1
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3859): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3859): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3859): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
D/SmartNS_Utility( 3859): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  907): acquireWL(43e4c588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{422d49e0: PendingIntentRecord{4289dfc8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821029, Int=1800000
,D/PMS     (  907): acquireWL(43ea2258): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{42f31108: PendingIntentRecord{43c807f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1857745, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42722c98: PendingIntentRecord{42930150 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450444548970, Int=900000
,D/PMS     (  907): releaseWL(43ea2258): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): releaseWL(43e4c588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43952188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43952188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43a0b120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43a0b120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(439f1140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4222d270: PendingIntentRecord{42225320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1903230, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(439f1140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5137): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5137): ====startRecUseTime====
D/htc.customization.log.level( 5137):  is 
W/CustomizationLogLevel( 5137): Level value is invalid, use default level 2
D/CustomizationManager( 5137):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5137): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5137): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5137): Parsing tag category name = system
I/CustomizationCIDLoader( 5137): Parsing tag category name = application
I/CustomizationCIDLoader( 5137): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5137): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5137): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5137): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5137): Parsing tag category name = Settings
D/CustomizationManager( 5137):  Read CID file spent 0.158 (s)
D/CustomizationManager( 5137):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 5137): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5137): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5137): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5137): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=5137, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  907): Copying FileAsset 0x6c2b9530 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{4245bf38 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SQLiteConnectionPool( 2197): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(443ea9f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
D/PMS     (  907): releaseWL(443ea9f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/[PluginManager]RegisterService( 1312): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1312): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/IcingCorporaProvider( 2864): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5152 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(42b9b0a8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2864): UpdateCorporaTask done [took 299 ms] updated apps [took 299 ms] 
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 5152): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5152): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5152): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5152): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5152): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5152): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5152): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5152): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5152): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5152): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5152): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5152): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5152): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5152): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5152): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5152): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5152): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5152): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5152): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5152): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5152): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5152): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5152): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5152): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5152): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5152): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5152): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5152): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5152): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5152): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5152): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5152): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5152): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5152): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5152): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5152): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5152): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5152): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5152): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5152): threadid=11: thread exiting with uncaught exception (group=0x41987e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5152): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5152): Process: com.google.android.apps.docs, PID: 5152
E/AndroidRuntime( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5152): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5152): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5152): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5152): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5152): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5152): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5152): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5152): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5152): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5152): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5152): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5152): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5152): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5152): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5152): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5152): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5152): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5152): Opened ClientFlag.db in read-only mode
D/Process ( 5152): killProcess, pid=5152
D/Process ( 5152): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5170 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 5152
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 5152) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 5170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5170): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5170): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5170): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5170): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5170): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5170): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5170): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5170): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5170): threadid=10: thread exiting with uncaught exception (group=0x41987e30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5183 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 5170): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5170): Process: com.android.keychain, PID: 5170
E/AndroidRuntime( 5170): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5170): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5170): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5170): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5170): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5170): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5170): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5170): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5183): getInstance(Context context)
D/Process ( 5170): killProcess, pid=5170
D/Process ( 5170): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450444633727.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 5183): getInstance(Context context)
D/AppTag  ( 5183): onCreate()
I/ActivityManager(  907): Recipient 5170
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 5170) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  907): acquireWL(435ded88): PARTIAL_WAKE_LOCK  AsyncService 0x1 3686 10160 null
D/PMS     (  907): releaseWL(435ded88): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4072): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2197): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2197): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2197): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2197): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2197): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2197): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2197): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2197): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66050d90
E/SQLiteLog( 2197): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2197): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x656aba40
W/dalvikvm( 2197): threadid=48: thread exiting with uncaught exception (group=0x41987e30)
E/DriveAsyncService( 2197): disk I/O error (code 3850)
E/DriveAsyncService( 2197): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2197): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2197): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2197): 	at java.lang.Thread.run(Thread.java:864)
W/PackageManager(  907): Unable to load service info ResolveInfo{43f29448 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 2197): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2197): Process: com.google.android.gms, PID: 2197
E/AndroidRuntime( 2197): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2197): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2197): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2197): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2197): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2197): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2197): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2197): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2197): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2197): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2197): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2197): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2197): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2197): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop151.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2197): killProcess, pid=2197
E/SQLiteDatabase( 2197): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2197): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad10 +
I/Prism.WidgetManager( 1269): onLoadItems() +
I/ActivityManager(  907): Recipient 2197
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2197) has died.
D/PMS     (  907): handleWLDeath(42b9b0a8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20994ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20994ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20993ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20990ms
E/SQLiteLog( 1368): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1368): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63ee8840
W/dalvikvm( 1368): threadid=1: thread exiting with uncaught exception (group=0x41987e30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1368): FATAL EXCEPTION: main
E/AndroidRuntime( 1368): Process: com.google.process.gapps, PID: 1368
E/AndroidRuntime( 1368): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1368): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1368): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1368): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1368): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1368): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1368): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1368): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1368): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1368): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1368): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1368): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1368): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1368): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1368): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1368): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1368): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1368): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1368): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop152.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1368): killProcess, pid=1368
D/Process ( 1368): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5212 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  907): Recipient 1368
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 1368) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20913ms

```
