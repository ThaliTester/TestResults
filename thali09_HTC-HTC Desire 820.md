#### Test 539786639813e59_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  916): setLight #0: color=#14
,--------- beginning of /dev/log/main
E/cutils-trace( 4570): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4570): ====startRecUseTime====
D/htc.customization.log.level( 4570):  is 
W/CustomizationLogLevel( 4570): Level value is invalid, use default level 2
D/CustomizationManager( 4570):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4570): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4570): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4570): Parsing tag category name = system
I/CustomizationCIDLoader( 4570): Parsing tag category name = application
I/CustomizationCIDLoader( 4570): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4570): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4570): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4570): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4570): Parsing tag category name = Settings
D/CustomizationManager( 4570):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4570):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4570): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4570): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4570): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4570): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  916): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  916): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  916): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  916): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  916): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  916): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  916): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4570
D/PMS     (  916): acquireHCC(444567c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 916 1000 null
D/PMS     (  916): acquireHCC(449f24c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 916 1000 null
W/asset   (  916): Copying FileAsset 0x6aef4fe8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  916): @test_code: getHtcIntentFlag: 0 obj: 1133331336
D/PMS     (  916): acquireWL(442257e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 916 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424c8e78
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
I/ActivityManager(  916): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4581 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4581): Copying FileAsset 0x5c80bc50 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4581): Binding Chromium to main looper Looper (main, tid 1) {42361640}
I/LibraryLoader( 4581): Expected native library version number "",actual native library version number ""
I/chromium( 4581): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4581): Initializing chromium process, renderers=0
D/PMS     (  916): acquireWL(43cbf310): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  916): acquireWL(441f7250): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  916): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  916): java.lang.Throwable: stack dump
D/BluetoothManagerService(  916): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4424eef8:true
W/System.err(  916): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  916): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  916): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  916): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  916): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4581): 1110929528: getState(). Returning 12
D/PMS     (  916): releaseWL(441f7250): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4581): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4581): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4581): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4581): Local Branch: 
I/Adreno-EGL( 4581): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4581): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4581):                  aa63bbd948f41d15fc72f585e
W/chromium( 4581): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4581): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4581): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4581): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4581): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4581): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4581): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4581): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4581): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4581): CordovaWebView is running on device made by: HTC
,W/AwContents( 4581): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  916): Disable input method client, pid=1274
W/ResourceType( 4581): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4581): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@423a8728, mServedView=org.apache.cordova.engine.SystemWebView{4236e390 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4581): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  916): Displayed com.test.thalitest/.MainActivity: +291ms
W/XT9_C   ( 1216): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1216): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1216): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1216): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  916): Enable input method client, pid=4581
D/PMS     (  916): releaseWL(442257e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4581): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4581): JniHelper::setJavaVM(0x41f1d010), pthread_self() = 1662504656
D/JX-Cordova( 4581): jxcore cordova android initializing
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 11.629MB for 146998-byte allocation
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 11.748MB for 220492-byte allocation
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 11.922MB for 330734-byte allocation
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 12.185MB for 496096-byte allocation
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 12.595MB for 744140-byte allocation
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 14.069MB for 1674304-byte allocation
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 15.503MB for 2511452-byte allocation
,I/SensorManager(  916): mEventCount = 900
,W/CpuWake (  916): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  916): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  916): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  916): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  916): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  916): <<release mCpuPerf_Freq wakelock
D/PMS     (  916): releaseHCC(444567c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  916): releaseHCC(449f24c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4581): Grow heap (frag case) to 17.548MB for 3767174-byte allocation
,W/jxcore-log( 4581): Initializing JXcore engine
,W/jxcore-log( 4581): JXcore engine is ready
,W/jxcore-log( 4581): Starting JXcore engine
,W/jxcore-log( 4581): Platform android
W/jxcore-log( 4581): 
,W/jxcore-log( 4581): Process ARCH arm
W/jxcore-log( 4581): 
,D/PMS     (  916): releaseWL(43cbf310): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4581): JXcore Cordova bridge is ready!
I/jxcore-log( 4581): 
,W/jxcore-log( 4581): JXcore engine is started
,I/chromium( 4581): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4581): Toggling radios to true
I/jxcore-log( 4581): 
,D/BluetoothAdapter( 4581): enable(): BT is already enabled..!
,D/WifiManager( 4581): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  916): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  916): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  916): Settings:Agentvalue: 2
W/Settings:Agent(  916): >> traceCallingStack()
W/Settings:Agent(  916): Process.myPid(): 916
W/Settings:Agent(  916): Process.myTid(): 1304
W/Settings:Agent(  916): Process.myUid(): 1000
W/Settings:Agent(  916): 
W/Settings:Agent(  916): 
,W/System.err(  916): java.lang.Throwable: stack dump
W/System.err(  916): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  916): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  916): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  916): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  916): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  916): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  916): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  916): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  916): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  916): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  916): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  916): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  916): 
W/Settings:Agent(  916): << traceCallingStack(): 1(ms)
,D/WifiManager( 4581): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  916): doBoolean: DISCONNECT
D/WifiManager( 4581): reconnect: Base Package Name=com.test.thalitest, uid=10389
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): TDLS: Tear down peers
I/wpa_supplicant( 1167): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4581): Radios toggled
I/jxcore-log( 4581): 
D/WifiService(  916): setWifiEnabled: true pid=4581, uid=10389
D/WifiService(  916): New client listening to asynchronous messages
E/WifiService(  916): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  916): isSprintWifiRestricted(): false
I/WifiService(  916): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  916): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1167): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1167): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1167): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb710bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1167): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1167): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless e,vent: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  916): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  916): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  916): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  916):    returned true,
D/WifiPerfLock(  916): release(),
D/WifiStateMachine(  916): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  916): [isWifi] getHotspotEnabled: false
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  916):    returned true
,D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  916): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  916): acquireWL(42ce3888): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 916 1000 null
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,D/DhcpStateMachine(  916): [RunningState] Stop DHCP
D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  916): doBoolean: RECONNECT
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): Fast associate: Old scan results
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=21997 mDataStallAlarmIntent=PendingIntent{42c77c78: PendingIntentRecord{42d46528 android broadcastIntent}}
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  916):    returned true
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  916): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  916): Exit handleNetworkDisconnect
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  916): Provision feature enable=false
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  916): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/UsbnetStateTracker(  916): isAvailable+-
D/UsbnetStateTracker(  916): reconnect
,D/UsbnetStateTracker(  916): isAvailable+-
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4207): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4207): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/MDST    (  916): default: reconnect()
D/MDST    (  916): default: setTeardownRequested(false)
D/MDST    (  916): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  916): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  916): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  916): New client listening to asynchronous messages
D/ConnectivityService(  916): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4207): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4207): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1370): Read error: ssl=0x63f71c60: I/O error during system call, Connection timed out
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/ConnectivityService(  916): resetConnections(wlan0, 3)
,V/NativeCrypto( 1370): SSL shutdown failed: ssl=0x63f71c60: I/O error during system call, Broken pipe
D/libc    (  365): [NET] entry_id:3   entry:0xb84998e0  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb849e348  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb849e090  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb849e428  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb849e190  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb849e4f0  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb849a000  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  916): acquireWL(4491eb30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
D/PMS     (  916): acquireWL(44a46790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
D/ConnectivityService(  916): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/ConnectivityService(  916): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  916): startScan Pid: 916 Uid 1000
,D/WifiNative-wlan0(  916): doBoolean: SCAN
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  916):    returned false
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): reportInetCondition for net -1, percentage: 0 by  (1370/10029)
D/BatSI   (  916): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  916): releaseWL(4491eb30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): mActiveDefaultNetwork: -1
D/ConnectivityService(  916): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  916): releaseWL(44a46790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  916): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4631 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  916): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  916): NoActiveNetworkState
D/Tethering(  916): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  916): bSetPropertyMultiRAB:false
,D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  916): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  916): ipv4Default null
,I/Tethering(  916): No IPv4 upstream interface, giving up.
,D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000),
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.docs (4428/10100)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
,D/PMS     (  916): acquireWL(4491b018): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/PMS     (  916): releaseWL(4491b018): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.docs (4428/10100)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,I/MusicStore( 4631): Database version: 95
,W/ContextImpl( 4631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4631, uid=10154, userID:0
,D/WifiDisplayAdapter(  916): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  916):     Client/Owner: Client
D/WifiDisplayAdapter(  916):     GroupId: 
D/WifiDisplayAdapter(  916):     Passphrase: 
D/WifiDisplayAdapter(  916):     SessionId: 0
D/WifiDisplayAdapter(  916):     IP Address: }
,D/MediaRouterService(  916): Client com.google.android.music (pid 4631): Registered
,D/WifiDisplayAdapter(  916): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  916):     Client/Owner: Client
D/WifiDisplayAdapter(  916):     GroupId: 
D/WifiDisplayAdapter(  916):     Passphrase: 
D/WifiDisplayAdapter(  916):     SessionId: 0
D/WifiDisplayAdapter(  916):     IP Address: }
I/MediaRouter( 4631): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.music (4631/10154)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (2793/10021)
,I/ActivityManager(  916): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4651 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4631): getSelectedRoute
,I/NetworkMonitor( 4631): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (4631/10154)
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4631, uid=10154, userID:0
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(43e639a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/ACRA    ( 4651): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  916): killProcessQuiet, pid=4363
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  916): releaseWL(43e639a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  916): Killing 4363:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/ACRA    ( 4651): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4651): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4363
D/WifiService(  916): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4651): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4651): Preparing secondary program dexes.
V/DexLibLoader( 4651): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4651): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4651): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4651): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4651): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4651): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4651): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4651): Dex already copied
D/OdexVerifier( 4651): Odex verification is skipped.
,V/DexLibLoader( 4651): Creating class loader
,V/DexLibLoader( 4651): Finished creating class loader
V/DexLibLoader( 4651): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4651): Dex already copied
D/OdexVerifier( 4651): Odex verification is skipped.
,V/DexLibLoader( 4651): Creating class loader,
V/DexLibLoader( 4651): Finished creating class loader
V/DexLibLoader( 4651): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4651): Dex already copied
D/OdexVerifier( 4651): Odex verification is skipped.
,V/DexLibLoader( 4651): Creating class loader,
,V/DexLibLoader( 4651): Finished creating class loader
V/DexLibLoader( 4651): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4651): Dex already copied
D/OdexVerifier( 4651): Odex verification is skipped.
,V/DexLibLoader( 4651): Creating class loader,
V/DexLibLoader( 4651): Finished creating class loader
,V/DexLibLoader( 4651): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4651): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4651): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1167): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-83
D/wpa_supplicant( 1167): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 3
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 1
I/wpa_supplicant( 1167): wpa_s->is_screen_on 1
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): selected network = 1
D/wpa_supplicant( 1167): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb710d4e8  current_ssid=0x0
D/wpa_supplicant( 1167): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1167): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1167): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1167): check if in concurrent case
I/wpa_supplicant( 1167): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  916): doString: LIST_DONGLES
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1167): RSN: PMKSA cache search - network_ctx=0xb710d4e8 try_opportunistic=0
D/wpa_supplicant( 1167): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1167): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1167): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1167): nl80211: Unsubscribe mgmt frames handle 0xb710c718 (mode change)
D/wpa_supplicant( 1167): nl80211: Subscribe to mgmt frames with non-AP handle 0xb710c718
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb710c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1167):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167):   * freq=2412
D/wpa_supplicant( 1167):   * Auth Type 0
D/wpa_supplicant( 1167):   * WPA Versions 0x2
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1167): nl80211: Connect request send successfully
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  916): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (489) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-48
I/wpa_supplicant( 1167): tsf=0000000104291154
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-51
I/wpa_supplicant( 1167): tsf=0000000104291170
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1167): freq=2427
I/wpa_supplicant( 1167): level=-83
I/wpa_supplicant( 1167): tsf=0000000104291174
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=Gonzos
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-51
I/wpa_supplicant( 1167): tsf=0000000104291166
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ####
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  916): getDiscoveryDongleList
,D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WirelessDisplayService(  916): getDiscoveryDongleList
,D/WifiManager( 1228): getScanResults enter 
D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/WifiStateMachine(  916): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 104291154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 104291170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2427, timestamp: 104291174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 104291166, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): add 4 to mScanResults
D/BatSI   (  916): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  916): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Connect event
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1167): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1167): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): TDLS: Remove peers on association
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1167): EAPOL: enable timer tick
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): Get randomness: len=32 entropy=5
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  916): interfaceStatusChanged wlan0, true
D/Tethering(  916): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  916): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  916): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  916): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  916): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  916): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  916): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb710c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa0b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1167):    broadcast key
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1167): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1167): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1167): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1167): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1167): set send_ind_to_ndc = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1167): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1167): EAPOL authentication completed successfully
I/wpa_supplicant( 1167): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  916): Enter handleAssociatedWithEvent
D/WifiStateMachine(  916): Associated
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  916): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  916): Exit handleAssociatedWithEvent
D/WifiStateMachine(  916): BSSID was changed, update WiFi database
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  916): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  916): updateConnectedAP...
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
D/Tethering(  916): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  916): updateConnectedAP...
D/Tethering(  916): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...,
,W/dalvikvm( 4651): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiStateMachine(  916): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  916): Provision feature enable=false
,D/ConnectivityService(  916): mActiveDefaultNetwork: -1
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4207): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4207): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  916): updateConnectedAP...
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,D/DhcpStateMachine(  916): [StoppedState] Start DHCP
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97,
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WifiStateMachine(  916): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  916): acquireWL(42fd8f28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 916 1000 null
,D/WifiStateMachine(  916): handlePreDhcpSetup mBluetoothConnectionActive: false
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  916):    returned null
E/WifiStateMachine(  916): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING STOP
D/BluetoothManagerService(  916): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/dalvikvm( 4651): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  916):    returned null
,I/jxcore-log( 4581): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): my name is : HTC-HTC Desire 820_PT9036
I/jxcore-log( 4581): 
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e54c68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42e54c68 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4581): attempting to connect to test coordinator
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): check test folder
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): found test : ./testFindPeers.js
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): found test : ./testReConnect.js
I/jxcore-log( 4581): 
,E/FbInjectorInitializer( 4651): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/jxcore-log( 4581): found test : ./testSendData.js
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): Test app app.js loaded
I/jxcore-log( 4581): 
,I/Choreographer( 4581): Skipped 158 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4581): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4581): 
,I/chromium( 4581): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/fb4a(:<default>):StaticBindingVerifier( 4651): Verify
,D/WifiService(  916): New client listening to asynchronous messages
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4651): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4651): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4651): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  916): killProcessQuiet, pid=3935
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  916): Killing 3935:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1348): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a48998
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  916): disable: get sensor name = CM36282 Light sensor
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a48998, eanble = 0, strlen(mName) = 59
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  916): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@428359a0
W/SensorService(  916): Listener[1] = com.htc.smartdim.sensor_eye@42fff510
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  916): Going to sleep due to screen timeout...
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1348/10055)
I/ActivityManager(  916): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  916): Couldn't get kernel wake lock stats
V/LightsService(  916): setLight #2: color=#0
D/qdlights(  916): set_light_buttons_func: on=0 brightness=0
V/LightsService(  916): setLight #0: color=#0
,D/WirelessDisplayService(  916): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  916): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  916): mWirelessDisplayManager is null
,I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4681 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1348): Util - no network available!
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1348/10055)
D/AutoSetting( 1348): service - onCreate()
D/AutoSetting( 1348): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1348): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  916): request 42e6f5c8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  916): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1348): service - mHandler: cancel location update
D/AutoSetting( 1348): service -           changes count: 0
,I/ActivityManager(  916): Recipient 3935
,W/fb4a(:<default>):UserScope( 4651): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4651): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4651): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/SurfaceControl(  916): Excessive delay in blankDisplay() while turning screen off: 319ms
D/PMS     (  916): nativeSetInteractive:false
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): nativeSetInteractive:false done
D/PMS     (  916): nativeSetAutoSuspend:true
D/PMS     (  916): nativeSetAutoSuspend:true done
D/HABCtrl (  916): TPE algorithm. remove timeout.
,D/PMS     (  916): OOBE c monitor 11
,I/InputManager(  916): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  916): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  916): Disable input method client, pid=4581
V/KeyguardServiceDelegate(  916): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42feb120)
W/ResourceType( 4581): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4581): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{4236e390 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1123): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
D/PMN     (  916): wakingUp
D/PMS     (  916): acquireWL(42cf5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,V/KeyguardServiceDelegate(  916): **** SHOWN CALLED ****
D/WirelessDisplayService(  916): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1255): applyRouting -2
I/WindowManager(  916): No lock screen! windowToken=null
D/PMN     (  916): onScreenOn
D/PMS     (  916): releaseWL(42cf5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  916): acquireWL(44226bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  916): releaseWL(44226bd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/MtpService( 2793): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1255): applyRouting - 0
,D/MtpService( 2793): [MTP][onReceive]-
D/PowerUI ( 1123): closing low battery warning: level=99
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/jxcore-log( 4581): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4581): 
,D/NfcService( 1255): applyRouting -2
D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/HtcPowerSaver(  916): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
D/PMS     (  916): acquireWL(43efcb10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  916): releaseWL(43efcb10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  916): batLight: plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c80000
D/qdlights(  916): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 1
,I/ClockThread( 1123): stop update clock
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:On
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  916):    returned true
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
D/AlarmManager(  916): ACTION_SCREEN_ON
I/AlarmManager(  916): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  916): [AlarmQueuing] done recovering
I/AlarmManager(  916): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  916): [AlarmQueuing] done EPS screen off alarm recovering
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/wpa_supplicant( 1167): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1167): EAPOL: disable timer tick
V/NotificationService(  916): batLight: plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c80000
D/qdlights(  916): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  916): updateScreenOn: false
D/MobileConnectivityChangeReceiver( 4681): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4681): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4681): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4681): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  916): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4707 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4681/10079)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4681/10079)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4681/10079)
,I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  916): acquireWL(445661e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4651): Grow heap (frag case) to 9.961MB for 84664-byte allocation
E/dalvikvm( 4651): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4651): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4651): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4651): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4651): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4651): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/PMS     (  916): releaseWL(445661e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(43eeaa08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(43eeaa08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
E/dalvikvm( 4651): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4651): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4651): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1749): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1749): onScreenOn: 1450361454597
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1749): onScreenOn: 1450361454597
E/dalvikvm( 4651): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4651): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4651): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4651): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4651): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4651): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4651): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4651): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4651): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  916): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4720 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  916): killProcessQuiet, pid=4141
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@428359a0
,W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,I/ActivityManager(  916): Killing 4141:com.google.android.talk/u0a111 (adj 15): empty #17
W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@428359a0, eanble = 0, strlen(mName) = 91
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  916): Listener[0] = com.htc.smartdim.sensor_eye@42fff510
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  916): goingToSleep
,D/PMS     (  916): acquireWL(443f8fc8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 916 1000 null
,I/dalvikvm-heap( 4651): Grow heap (frag case) to 10.043MB for 39954-byte allocation
D/PMS     (  916): releaseWL(443f8fc8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4651): Grow heap (frag case) to 10.120MB for 79892-byte allocation
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4720): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4720): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  916): Recipient 4141
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4651): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4720/10151)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d041f8 u0 ReceiverList{43d040f8 4651 com.facebook.katana/10027/u0 remote:43b0b820}}
,V/WebViewChromiumFactoryProvider( 4720): Binding Chromium to main looper Looper (main, tid 1) {42366408}
,I/LibraryLoader( 4720): Expected native library version number "",actual native library version number ""
,I/chromium( 4720): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4720): Initializing chromium process, renderers=0
W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d041f8 u0 ReceiverList{43d040f8 4651 com.facebook.katana/10027/u0 remote:43b0b820}}
W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4302fef8 u0 ReceiverList{4302fe98 4651 com.facebook.katana/10027/u0 remote:441fc988}}
,E/AudioManagerAndroid( 4720): BLUETOOTH permission is missing!
D/PMS     (  916): acquireWL(43fbbd60): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  916): acquireWL(44358258): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,I/Adreno-EGL( 4720): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4720): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4720): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4720): Local Branch: 
I/Adreno-EGL( 4720): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4720): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4720):                  aa63bbd948f41d15fc72f585e
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
D/PMS     (  916): releaseWL(44358258): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,I/NSApplication( 4720): Starting up...
D/AlarmManager(  916): ACTION_SCREEN_OFF
I/AlarmManager(  916): [AlarmQueuing] screen off now: 
I/AlarmManager(  916): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=21998 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:Off
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1167): get_ip_address source addr = 02000000
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  916):    returned true
I/AlarmManager(  916): [AlarmQueuing] wifi connection: true
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4720/10151)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4720/10151)
D/PMS     (  916): acquireWL(43327fc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 916 1000 null
D/PMS     (  916): releaseWL(43327fc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  916): updateScreenOn: false
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/Process (  916): killProcessQuiet, pid=4398
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
I/ActivityManager(  916): Killing 4398:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  916): acquireWL(44471508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(44471508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
I/ActivityManager(  916): Recipient 4398
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
I/iu.Environment( 2185): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 2185): num queued entries: 0
I/iu.UploadsManager( 2185): num updated entries: 0
,I/iu.SyncManager( 2185): NEXT; no task
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/AutoSetting( 1348): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/AutoSetting( 1348): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/TetherSettings( 4207): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4207): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4207): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4207): Cust_ConnectToPC   : spcsc>false
D/        ( 4207): Cust_ConnectToPC   : IPT>true
,D/        ( 4207): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4207): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4207): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4207): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4207): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4207): onReceive:android.intent.action.USER_PRESENT
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4207): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4207): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4207):  defaultType:0
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  916): acquireWL(43cae560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(43cae560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(43eb7750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1749): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1749): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1749): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1749): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1749): onScreenOff
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  916): releaseWL(43eb7750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4651): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/AutoSetting( 1348): service - mHandler: cancel location update
,D/AutoSetting( 1348): service -           changes count: 0
I/ActivityManager(  916): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4769 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4769): isEpsOn(), nState = 0
D/PMS     (  916): acquireWL(443bebe0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4769 1000 null
,D/PMS     (  916): releaseWL(443bebe0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4769): getMobilePolicyEnabled, result = true
D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  916): Killing 4428:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  916): killProcessQuiet, pid=4428
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4769): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4769): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4769): getMobilePolicyEnabled, result = true
D/WifiService(  916): New client listening to asynchronous messages
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fff510
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 1
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fff510, eanble = 0, strlen(mName) = 36
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  916): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 0
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fff510, eanble = 0, strlen(mName) = 36
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fff510
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  916): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fffa58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fffa58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  916): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  916): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  916): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  916): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  916): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  916): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  916): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  916): Recipient 4428
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  916): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  916): releaseWL(42fd8f28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): gateway: /192.168.1.1
,D/WifiNative-wlan0(  916): doBoolean: DRIVER GATEWAY-ADD 16885952
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  916): VerifyingLinkState enter
D/WifiStateMachine(  916): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  916): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  916): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  916): WAN detection
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  916): Provision feature enable=false
D/ConnectivityService(  916): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  916): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  916): default: teardown()
D/MDST    (  916): default: setTeardownRequested(true)
D/MDST    (  916): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  916): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  916): default: setTeardownRequested(true)
D/ConnectivityService(  916): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  916): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ce3650
,D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WISPrService( 4207): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  916): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): syncGetConfiguredNetworks
D/ConnectivityService(  916): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  916): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  916): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  916): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  916): acquireWL(44447ee8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  916): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4681/10079)
,D/WirelessDisplayService(  916): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  916):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1123): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  916): acquireWL(44240ed0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44240e80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(44240ed0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2185): Checkin interval check for package: unspecified last checkin: 1450361407090 min interval config: 0 actual interval: 48492
,I/CheckinService( 2185): Checking schedule, now: 1450361455589 next: 1450361437055
,I/CheckinService( 2185): active receiver: enabled
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
,I/CheckinService( 2185): Preparing to send checkin request
,I/EventLogService( 2185): Accumulating logs since 1450361402220
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  916): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  916): releaseWL(44447ee8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2185): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2185): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2185/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  916): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4822 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4822): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4822): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4822): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4822): install
,I/MultiDex( 4822): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4822): loading existing secondary dex files
,I/MultiDex( 4822): load found 3 secondary dex files
,I/MultiDex( 4822): install done,
,W/dalvikvm( 4822): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4822): VFY: unable to resolve instance field 36
,W/dalvikvm( 4822): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4822): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4822): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4822): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4822): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1228): callingUid 10029, callindPid: 1228
,W/dalvikvm( 4822): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4822): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4822): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4822): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4822): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2185): Restart initialization of location
,E/MDM     ( 1228): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1228): No location to return for getLastLocation()
,W/FusedLocationProvider( 1228): location=null
D/PMS     (  916): acquireWL(42bc6a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42bc6a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4822): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=598048931
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3416893162
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/PMS     (  916): releaseWL(42ce3888): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  916): NetTransition Wakelock for ConnectedState released by timeout
,W/Settings( 4822): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: true
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
V/Tethering(  916): bSetPropertyMultiRAB:false
,D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  916): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
I/Tethering(  916): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  916): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/PMS     (  916): acquireWL(42d355b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): releaseWL(42d355b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (4631/10154)
I/Tethering(  916): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  916): Found interface wlan0
D/CaptivePortalTracker(  916): NoActiveNetworkState
D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 4631): type=WIFI subType= reason=null isConnected=true
,D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1578/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.musicenhancer (3994/10053)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4681/10079)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
D/PMS     (  916): acquireWL(4373a788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/PMS     (  916): releaseWL(4373a788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(439ed4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/PMS     (  916): releaseWL(439ed4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (2793/10021)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1336): Unsupported attribute readOnly
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1348): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/MobileConnectivityChangeReceiver( 4681): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4681): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1348/10055)
,D/AutoSetting( 1348): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1348): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1348): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1348): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4720/10151)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1348/10055)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
,D/PMS     (  916): acquireWL(442203c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2185): Checkin interval check for package: unspecified last checkin: 1450361407090 min interval config: 0 actual interval: 49596
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(442203c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 13.521MB for 1821008-byte allocation
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2185): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2185): num queued entries: 0
,I/iu.UploadsManager( 2185): num updated entries: 0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
I/iu.SyncManager( 2185): NEXT; no task
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1370): [NET] getaddrinfo-, 1
,D/libc    ( 1370): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e6a1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/PMS     (  916): acquireWL(42e4de00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 184
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1370): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1370): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4651): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4651): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/PMS     (  916): acquireWL(43765a30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4651): Called registerBroadcastReceiver twice.
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/PMS     (  916): releaseWL(42e4de00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  916): handleInetConditionChange: starting a change hold
,D/PMS     (  916): releaseWL(43765a30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4349f450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
,D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
,D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(4349f450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,I/Adreno-EGL( 4822): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4822): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4822): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4822): Local Branch: 
I/Adreno-EGL( 4822): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4822): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4822):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4651/10027)
,I/Adreno-EGL( 4822): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4822): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4822): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4822): Local Branch: 
I/Adreno-EGL( 4822): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4822): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4822):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4822): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4822): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4822): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4822): Local Branch: 
I/Adreno-EGL( 4822): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4822): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4822):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4581): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4581): 
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (4822/10029)
,I/CheckinRequestBuilder( 2185): Classify the device as Phone.
,D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2185): [NET] getaddrinfo-,err=8
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2185): [NET] getaddrinfo-, 1
,D/libc    ( 2185): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4fe7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 44
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2185): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2185): [NET] getaddrinfo-,err=8
,D/PMS     (  916): acquireWL(42efafb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4631 10154 null
,W/ContextImpl( 4631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4631, uid=10154, userID:0
,I/MusicLeanback( 4631): Conditions not met for autocaching.
,I/MusicLeanback( 4631): Stop autocaching.
,W/ContextImpl( 4631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  916): releaseWL(42efafb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  916): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [15][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2185): [NET] getaddrinfo-,err=8
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2185): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2185): Sending checkin request (12079 bytes)
,D/PMS     (  916): releaseWL(43fbbd60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 2185): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2185): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2185/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [11][0][0]
,I/CheckinRequestBuilder( 2185): Classify the device as Phone.
,I/CheckinTask( 2185): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2185): Checking schedule, now: 1450361458117 next: 1450884395111
,I/CheckinService( 2185): active receiver: disabled
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,I/CheckinService( 2185): Checking schedule, now: 1450361458152 next: 1450884395111
,I/CheckinService( 2185): active receiver: disabled
,D/CheckinService( 2185): Recording last checkin time for package unspecified as 1450361458159
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(44240e80): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  916): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
,D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ba16 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  916): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  916): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4581): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4581): threadid=1: thread exiting with uncaught exception (group=0x41f2ee30)
,E/AndroidRuntime( 4581): FATAL EXCEPTION: main
E/AndroidRuntime( 4581): Process: com.test.thalitest, PID: 4581
E/AndroidRuntime( 4581): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4581): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4581): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4581): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4581): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4581): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 4581): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4581): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4581): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4581): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4581): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4581): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4581): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4581): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4581): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4581): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4581): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4581): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4581): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  916): App crashed! Process: com.test.thalitest
W/ActivityManager(  916):   Force finishing activity com.test.thalitest/.MainActivity
D/Process (  916): killProcessQuiet, pid=4452
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4581): killProcess, pid=4581
,D/Process ( 4581): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  916): Killing 4452:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4452
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  916): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  916): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1216): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  916): Got RemoteException sending setActive(false) notification to pid 4581 uid 10389
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4581
,I/WindowState(  916): WIN DEATH: Window{43d17bd0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  916): Client connection lost with reason: 4
,I/ActivityManager(  916): Process com.test.thalitest (pid 4581) has died.
,I/GAV2    ( 4720): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  916): acquireWL(4494ff68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4494ff68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  916): killProcessQuiet, pid=4415
,I/ActivityManager(  916): Killing 4415:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 4415
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
,I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4878 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
,W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1336): Unsupported attribute readOnly
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4878): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4878): MmsConfig.loadMmsSettings
,W/dalvikvm( 4878): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4878): VFY: unable to resolve instance field 36
,W/dalvikvm( 4878): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4878, uid=10111, userID:0
,W/Settings( 4878): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  916): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4901 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4878, uid=10111, userID:0
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4878, uid=10111, userID:0
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4878, uid=10111, userID:0
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4878, uid=10111, userID:0
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4878, uid=10111, userID:0
,D/PMS     (  916): acquireWL(43ce3008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4878 10111 null
,I/[PluginManager]RegisterService( 1348): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1348): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  916): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/MessageFrequencyProvider( 4901): onCreate
I/ActivityManager(  916): Resuming delayed broadcast
,V/GetPrviateResource( 4901): GetPrviateResource
,V/GetPrviateResource( 4901): GetPrviateResource
,D/MmsCustomizationProvider( 4901): query uri: content://htc-mms-customization/mms-ua/ua_string
I/ActivityManager(  916): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4901): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4878): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4878): MmsConfig.loadFromDatabase
D/PMS     (  916): acquireWL(443f93b8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(443f93b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4494f288): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4878): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4878): MmsConfig.loadFromResources
,E/Babel   ( 4878): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4878): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4878): Installed default security provider GmsCore_OpenSSL
,D/Process (  916): killProcessQuiet, pid=4471
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  916): releaseWL(43ce3008): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  916): Killing 4471:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/MessageCustFlag( 4901): sense_version=6.0
D/BTAccessoryUtil( 4901): createReceiver
D/BTAccessoryUtil( 4901): registerReceiver return intent = null
D/MessageCustFlag( 4901): sku_id=99
W/SystemReader( 4901): Cannot find message_ambs_application_id, use default value instead
,I/ActivityManager(  916): Recipient 4471
,D/Messaging( 4901): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4901): networkCode: 
D/MessageCustFlag( 4901): sku_id=99
D/MmsConfig( 4901): SIE smsPri: null
,D/MmsConfig( 4901): networkCode: 
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcTelephonyCapability( 4901): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4901): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4901): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4901): Cannot find qct_8960_interface, use default value instead
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  916): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  916): releaseWL(4494f288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(44205758): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  916): releaseWL(44205758): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(44909f00): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  916): acquireWL(43f1f870): PARTIAL_WAKE_LOCK  AsyncService 0x1 4186 10160 null
,D/PMS     (  916): releaseWL(43f1f870): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
,D/PMS     (  916): releaseWL(44909f00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
D/PMS     (  916): acquireWL(42f31580): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  916): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  916): releaseWL(42f31580): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  916): acquireWL(433d8cd0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(433d8cd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  916): acquireWL(4386f7a0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4386f7a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(44448aa0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@423f1bd0 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
D/PMS     (  916): releaseWL(44448aa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 970 ms] updated apps [took 970 ms] 
,I/PackageBroadcastService( 2185): Null package name or gms related package.  Ignoreing.
,D/PMS     (  916): acquireWL(44a3ea18): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  916): killProcessQuiet, pid=3994
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 3994:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  916): Recipient 3994,
,I/Icing   ( 2185): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  916): Resuming delayed broadcast
,W/PackageManager(  916): Unable to load service info ResolveInfo{43482648 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  916): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  916): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  916): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  916): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  916): 	at dalvik.system.NativeStart.main(Native Method)
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@423f1bd0 -
,D/RemoteDisplayProvider(  916): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  916): start
,I/GCoreNlp( 1228): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/LocationProviderProxy(  916): applying state to connected service
D/PMS     (  916): acquireWL(42bd87a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42bd87a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  916): applying state to connected service
D/PMS     (  916): acquireWL(428d3ed0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(428d3ed0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42f4e450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42f4e450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(42ea6490): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42ea6490): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4901): mNeedToUpdateDate2 start
,D/MmsConfig( 4901): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4901): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4901): 
D/MmsAsyncWorkHandler( 4901): HM tk = 20001
,D/SettingsManager( 4901): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@42368860
,D/ReportIndicatorCache( 4901): MSG_QUERY_REPORTS >>
,I/Messaging( 4901): mccmnc> 
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/DraftCache( 4901): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4901): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4901): networkCode: 
,D/Messaging( 4901): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 59
,D/AccFlag ( 1244): sku_id=99
D/PhoneStorageUtil( 4901): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4901): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4901): createReceiver
,D/MessageCustFlag( 4901): sense_version=6.0
,D/Jerry   ( 4901): start to preload cursor >>>>>>>
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4901): [DraftCache/487] rebuildCache
,D/TelephUtils( 1244): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,V/MmsProvider( 1244): Update uri=content://mms, match=0
,V/MmsProvider( 1244): selection=st=129 AND m_type!=134
D/Messaging( 4901): mNeedToUpdateDate2: false
D/Messaging( 4901): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4901): TransactionService is going to be woken up.
,V/TransactionService( 4901): 1-Creating TransactionService
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 59
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1244):  phoneType = -1
V/TransactionService( 4901): onStartCommand: 1
,D/MmsSystemEventReceiver( 4901): unRegisterForConnectionStateChanges
V/TransactionService( 4901): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4901): Loading previous transactions.
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1244): device_type: 1
,D/TransactionService( 4901): Force set service start id to 1
V/TransactionService( 4901): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4901): unRegisterForConnectionStateChanges
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 59
,D/Jerry   ( 1244): URI_DRAFT
,D/Messaging( 4901): ViewCache CreatePreload
D/Messaging( 4901): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TransactionService( 4901): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4901): Destroying TransactionService
D/DraftCache( 4901): hasDraft() = false mNeedNotifyChange = true
,V/TransactionService( 4901): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4901): [DraftCache/487] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4901): 
D/MmsAsyncWorkHandler( 4901): HM tk = 20002
,D/Cust_MMSMS( 4901): _has_set_default_values_2=true
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MsgPreferenceUtils( 4901): def_index: 0
,D/Messaging( 4901): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4901): globalIndex = 1
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 59
,D/AccFlag ( 1244): sku_id=99
D/MsgPreferenceUtils( 4901): phone state: true
D/MsgPreferenceUtils( 4901): sd state: false
,D/MsgPreferenceUtils( 4901): vIndex = 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1244): sku_id=99
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  916): releaseWL(44a3ea18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{441f1be0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4878): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(434608c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/PMS     (  916): releaseWL(434608c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=99
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(42c3c768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{4420ee58: PendingIntentRecord{4308ad88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124584, Int=0
,D/PMS     (  916): acquireWL(42fcdb18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{425644b8: PendingIntentRecord{430b6178 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135851, Int=0
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [12][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/PMS     (  916): acquireWL(42ecade8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42fcdb18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42ecade8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,D/PMS     (  916): releaseWL(42c3c768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43944380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): acquireWL(42d7f148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(43944380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42b8b2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(42b8b2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42d7f148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e0c8b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302,
,D/PMS     (  916): releaseWL(42e0c8b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42dc6db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(42dc6db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44946c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): acquireWL(42f7ed40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1228): Vacuum at: now=1450361485351 tag=VacuumService
,D/PMS     (  916): acquireWL(44502790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42f7ed40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(44946c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44a9c940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(44a9c940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(430b4a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(430b4a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1228): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1228): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
,D/libc    ( 1228): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fda3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18789
D/libc    (  365): [NET]res_nsend:resplen=45
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1228): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,W/PhenotypeConfigurator( 1228): Server returned 404
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
D/PMS     (  916): acquireWL(4494b7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
D/PMS     (  916): releaseWL(44502790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4435bf18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4435bf18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4494b7e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42ec8b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(42ec8b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  916): acquireWL(434a90d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(434a90d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43b58ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(43b58ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1348): service - has update message, not stop
,D/AutoSetting( 1348): service - mHandler: update timezone
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1514): service - onCreate()
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  916): batLight: plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1514): service - mHandler: update timezone
V/LightsService(  916): setLight #8: color=#c80000
D/qdlights(  916): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1514): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1514): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{424aaff0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 1 7 2 11
,D/PMS     (  916): acquireWL(448b2f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{42b76c10: PendingIntentRecord{42bc2408 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143449, Int=0
,D/GpsLocationProvider(  916): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  916): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  916): acquireWL(42ff6290): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/PMS     (  916): releaseWL(448b2f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
,D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4f70 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  916): [NET] getaddrinfo_proxy-, success
I/global  (  916): call createSocket() return a new socket.
D/libc    (  916): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  916): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  916): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  916): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  916):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  916): releaseWL(42ff6290): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{43296250 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  916): acquireWL(43f2b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43f2b4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1348): service - handleMessage() stop self
,D/AutoSetting( 1348): service - onDestroy() END
,D/AutoSetting( 1348): service - handleMessage() quit looper
,D/Process (  916): killProcessQuiet, pid=4508
,I/ActivityManager(  916): Killing 4508:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 4508
,D/AutoSetting( 1514): service - handleMessage() stop self
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1514): service - onDestroy() END
,D/Process (  916): killProcessQuiet, pid=4522
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Killing 4522:com.android.settings:remote/1000 (adj 15): empty #17
D/AutoSetting( 1514): service - handleMessage() quit looper
,I/ActivityManager(  916): Recipient 4522
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(433788a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(433788a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  916): acquireWL(441f7468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
I/BatteryService(  916): n_update end
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=99
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(441f7468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1370): disconnect managed GoogleApiClient
,D/PMS     (  916): acquireWL(448c2698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(448c2698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderNotification, total:0
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1603): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4207): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4207): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4207): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4207): Cust_ConnectToPC   : spcsc>false
D/        ( 4207): Cust_ConnectToPC   : IPT>true
D/        ( 4207): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4207): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4207): Index of the first 1 = -1
W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4207): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4207): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4207): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_NSReceiver( 4207): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4207): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(44550280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10027}
,V/AlarmManager(  916): sending alarm PendingIntent{43d14f10: PendingIntentRecord{4451e610 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225693, Int=0
,I/ActivityManager(  916): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4983 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  916): sending alarm PendingIntent{42ebbfb0: PendingIntentRecord{42ec91b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450361562063, Int=10800000
,V/AlarmManager(  916): sending alarm PendingIntent{4453f220: PendingIntentRecord{4451e610 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225736, Int=0
,V/AlarmManager(  916): sending alarm PendingIntent{42dbfda8: PendingIntentRecord{4402b710 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=225744, Int=120000
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(44550280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.aurora (4983/10049)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/Process (  916): killProcessQuiet, pid=4325
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4325:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4325
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(4420ece0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4420ece0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(448f0988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(448f0988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(43f52af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290877, Int=0
,D/PMS     (  916): releaseWL(43f52af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(43ae2600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43ae2600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(44400e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44400e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
,I/HtcPowerSaver(  916): >> updateStatus
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(448f6d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=350877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(448f6d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(443ffd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(443ffd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(431fefd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(431fefd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(4403c628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4403c628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(44921d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=470878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44921d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(43cb6cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43cb6cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(44503470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10027}
,V/AlarmManager(  916): sending alarm PendingIntent{448d5f28: PendingIntentRecord{4402b710 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=525758, Int=300000
,V/AlarmManager(  916): sending alarm PendingIntent{43b70660: PendingIntentRecord{43085798 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450361677850, Int=1800000
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): acquireWL(43e322e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(44503470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  916): acquireWL(443ff760): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(43e322e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2185): Aggregate from 1450361455623 (log), 1450359877710 (data)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(443ff760): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43b2c6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=530878, Int=0
,D/PMS     (  916): releaseWL(43b2c6d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(448c3828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(448c3828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(432f54a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=590877, Int=0
I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(432f54a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(441ceed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(441ceed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/Process (  916): killProcessQuiet, pid=4552
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4552:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4552
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(443f5c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=650877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.707MB for 50416-byte allocation
D/PMS     (  916): releaseWL(443f5c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43e3b5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43e3b5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42e71f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=710877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42e71f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43cd5258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43cd5258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42e88bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=770878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42e88bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44abd750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44abd750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(448ca108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=830877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(448ca108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43dda478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43dda478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(43475850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=890878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.707MB for 50416-byte allocation
D/PMS     (  916): releaseWL(43475850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(441c0078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(441c0078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4329d390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{42570be8: PendingIntentRecord{42cede08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784765, Int=0
,D/ConnectivityService(  916): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  916): sending alarm PendingIntent{42db0d00: PendingIntentRecord{42db4228 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450362282514, Int=900000
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  916): releaseWL(4329d390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  916): Done.
,D/ConnectivityService(  916): Setting timer for 720seconds
D/PowerUsageService( 4769): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4769): MY_DEBUG = false
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,D/PMS     (  916): acquireWL(42debfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950877, Int=0
,D/PMS     (  916): releaseWL(42debfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42d50318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42d50318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42d19628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{448fdc90: PendingIntentRecord{43224758 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450362355333, Int=0
,D/SmartSyncUtils( 4769): isEpsOn(), nState = 0
D/PMS     (  916): acquireWL(42ccbcc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4769 1000 null
D/PMS     (  916): releaseWL(42d19628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4769): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4769): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4769): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 4769): SettingOnTime = 1450418400000, randomSettingOnTime = 1450418334000
D/SmartSyncScreenOnOffTimeReceiver( 4769): SettingOffTime = 1450404000000, randomSettingOffTime = 1450408932000
,D/SmartSyncScreenOnOffTimeReceiver( 4769): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4769): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4769): bNightModeTurnOffOnce = false
D/PMS     (  916): releaseWL(42ccbcc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  916): acquireWL(42c5b0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{441ce450: PendingIntentRecord{430a57a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1007930, Int=0
,D/PMS     (  916): acquireWL(42bec728): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42bec728): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42c5b0f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42b7d358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [119][1][0]
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): acquireWL(42c3d838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42b7d358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1228): Scheduling Phenotype for one-off execution 948 seconds from now (1450362357539)
,D/GetConfigurationSnapshotOperation( 1228): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1228): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1228): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1228): [NET] getaddrinfo-, 1
,D/libc    ( 1228): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a5c6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/PMS     (  916): acquireWL(42fca738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42fca738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1228): [NET] getaddrinfo_proxy-, success
D/PMS     (  916): acquireWL(42dccb80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  916): handleInetConditionChange: starting a change hold
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(42dccb80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
D/libc    ( 1228): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1228): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=7 [14][1][0]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1228/10029)
,D/PMS     (  916): releaseWL(42c3d838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  916): acquireWL(43cc4240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(43cc4240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42e89fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026319
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026381
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026385
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026389
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360026397
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027822
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360027861
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360030302
,D/PMS     (  916): releaseWL(42e89fa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4451c460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4451c460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42dc8d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1070878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.707MB for 50416-byte allocation
,D/PMS     (  916): releaseWL(42dc8d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43d400c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43d400c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42cb23c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42cb23c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42c7b000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1130877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42c7b000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42efbdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42efbdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(43395530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1190877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(43395530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44401fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44401fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  916): acquireWL(42b84160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1250878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42b84160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43292b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43292b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(448fb9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1310877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(448fb9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(4374d7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4374d7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(44522b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1370877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44522b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(434b8588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(434b8588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(44400028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1430878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  916): releaseWL(44400028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42e0bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42e0bd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4303d5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1490877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4303d5f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(444339e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(444339e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42c85558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1550878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42c85558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44180c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PowerUI ( 1123): closing low battery warning: level=100
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PMS     (  916): releaseWL(44180c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42cb6148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42cb6148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42f71700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1610878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42f71700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(449b8080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(449b8080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(42f04730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1670878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.707MB for 50416-byte allocation
D/PMS     (  916): releaseWL(42f04730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43fb43b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43fb43b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(44920a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1730877, Int=0
I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44920a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f08940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): releaseWL(42f08940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  916): updateBatteryInfo
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,D/TetherSettings( 4207): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4207): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4207): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4207): Cust_ConnectToPC   : spcsc>false
D/        ( 4207): Cust_ConnectToPC   : IPT>true
D/        ( 4207): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4207): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4207): Index of the first 1 = 3
W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4207): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4207): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4207): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4207): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4207): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(42ff9fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/PMS     (  916): releaseWL(42ff9fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(44aae688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1790878, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44aae688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f54000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): releaseWL(42f54000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  916): updateBatteryInfo
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,D/PMS     (  916): acquireWL(444421d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  916): BroadcastReceiver::onReceive+
,D/UsbnetService(  916): onReceive BATTERY_CHANGED
,D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(444421d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  916): acquireWL(4306da20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{42570be8: PendingIntentRecord{42cede08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1653418, Int=0
V/AlarmManager(  916): sending alarm PendingIntent{42c5b048: PendingIntentRecord{42dc3860 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1823074, Int=1800000
V/AlarmManager(  916): sending alarm PendingIntent{424c0278: PendingIntentRecord{42d54190 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1826881, Int=0
D/ConnectivityService(  916): Sampling interval elapsed, updating statistics ..,
,D/PMS     (  916): acquireWL(43b5e828): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
,D/ConnectivityService(  916): Done.
,D/ConnectivityService(  916): Setting timer for 720seconds
,I/ProcessStatsService(  916): Prepared write state in 37ms
,D/PMS     (  916): releaseWL(43b5e828): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  916): acquireWL(43df2b88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 916 1000 null
,D/PMS     (  916): releaseWL(4306da20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  916): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-30-40.bin
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(434e70d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/PMS     (  916): releaseWL(43df2b88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  916): releaseWL(434e70d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  916): acquireWL(42ef9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1850877, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(42ef9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42f4a350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
,I/BatteryService(  916): n_update end
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(42f4a350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(43dd2408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43dd2408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5031): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5031): ====startRecUseTime====
D/htc.customization.log.level( 5031):  is 
W/CustomizationLogLevel( 5031): Level value is invalid, use default level 2
D/CustomizationManager( 5031):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5031): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5031): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5031): Parsing tag category name = system
I/CustomizationCIDLoader( 5031): Parsing tag category name = application
I/CustomizationCIDLoader( 5031): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5031): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5031): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5031): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5031): Parsing tag category name = Settings
D/CustomizationManager( 5031):  Read CID file spent 0.156 (s)
D/CustomizationManager( 5031):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 5031): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5031): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5031): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5031): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  916): deletePackageAsUser: pkg=com.test.thalitest, pid=5031, uid=2000 user=0
D/Process (  916): killProcessQuiet, pid=4631
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  916): killProcessQuiet, pid=4720
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  916): Killing 4631:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  916): Killing 4720:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  916): killProcessQuiet, pid=4707
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  916): killProcessQuiet, pid=4681
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  916): Killing 4707:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  916): Killing 4681:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
I/ActivityManager(  916): Recipient 4681
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4707
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  916): Copying FileAsset 0x69c607d8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  916): Skipping PackageSetting{42a07738 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4631
D/MediaRouterService(  916): Client com.google.android.music (pid 4631): Died!
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4720
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  916): acquireWL(43ee6210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1228 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1228): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  916): releaseWL(43ee6210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1305): Cleaning up data for package: com.test.thalitest
D/PMS     (  916): acquireWL(43fc59f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{428215d8: PendingIntentRecord{42816570 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1910877, Int=0
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1348): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1348): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mmsto"
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/InputMethodManagerService(  916): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
I/IcingCorporaProvider( 2581): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
E/ExternalAccountType( 1336): Unsupported attribute readOnly
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  916): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5045 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  916):   Scheme: "mmsto"
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  916): acquireWL(442279b0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2581): UpdateCorporaTask done [took 421 ms] updated apps [took 420 ms] 
E/SQLiteDatabase( 5045): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5045): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5045): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5045): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5045): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5045): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5045): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5045): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5045): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5045): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5045): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5045): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5045): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5045): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5045): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5045): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5045): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5045): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5045): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5045): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5045): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5045): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5045): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5045): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5045): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5045): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5045): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5045): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5045): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5045): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5045): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5045): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5045): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5045): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5045): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5045): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5045): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5045): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5045): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5045): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5045): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5045): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5045): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5045): threadid=11: thread exiting with uncaught exception (group=0x41f2ee30)
E/ActivityManager(  916): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5045): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5045): Process: com.google.android.apps.docs, PID: 5045
E/AndroidRuntime( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5045): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5045): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5045): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5045): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5045): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
E/SQLiteDatabase( 5045): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5045): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5045): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5045): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5045): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5045): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5045): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5045): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5045): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5045): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5045): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5045): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5045): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5045): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5045): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5045): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5045): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5045): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5045): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5045): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5045): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5045): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5045): Opened ClientFlag.db in read-only mode
D/Process ( 5045): killProcess, pid=5045
I/ActivityManager(  916): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5063 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 5045): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  916): Recipient 5045
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Process com.google.android.apps.docs (pid 5045) has died.
W/ContextImpl( 5063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5063): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5063): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5063): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5063): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5063): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5063): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5063): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5063): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5063): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5063): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5063): threadid=10: thread exiting with uncaught exception (group=0x41f2ee30)
E/AndroidRuntime( 5063): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5063): Process: com.android.keychain, PID: 5063
E/AndroidRuntime( 5063): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5063): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5063): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5063): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5063): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5063): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5063): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5063): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5063): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  916): App crashed! Process: com.android.keychain
I/ActivityManager(  916): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5079 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  916): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5079): getInstance(Context context)
D/Process ( 5063): killProcess, pid=5063
D/Process ( 5063): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  916): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  916): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450363261202.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  916): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  916): 	... 4 more
I/ActivityManager(  916): Recipient 5063
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Process com.android.keychain (pid 5063) has died.
W/ActivityManager(  916): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5079): getInstance(Context context)
D/AppTag  ( 5079): onCreate()
D/PMS     (  916): acquireWL(42592fc8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4186 10160 null
D/PMS     (  916): releaseWL(42592fc8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4224): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2185): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2185): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  916): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2185): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2185): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x652bde98
E/SQLiteLog( 2185): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2185): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65b4e8a8
W/dalvikvm( 2185): threadid=50: thread exiting with uncaught exception (group=0x41f2ee30)
E/AndroidRuntime( 2185): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2185): Process: com.google.android.gms, PID: 2185
E/AndroidRuntime( 2185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2185): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2185): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2185): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2185): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2185): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2185): 	at java.lang.Thread.run(Thread.java:864)
E/DriveAsyncService( 2185): disk I/O error (code 3850)
E/DriveAsyncService( 2185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2185): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  916): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2185): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2185): killProcess, pid=2185
D/Process ( 2185): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  916): Client connection lost with reason: 4
D/PMS     (  916): handleWLDeath(442279b0): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  916): Recipient 2185
I/ActivityManager(  916): Process com.google.android.gms (pid 2185) has died.
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20996ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20995ms
I/ActivityManager(  916): Resuming delayed broadcast
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@423f1bd0 +
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20985ms
I/Prism.WidgetManager( 1274): onLoadItems() +
E/SQLiteLog( 1370): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1370): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca2b438
W/dalvikvm( 1370): threadid=1: thread exiting with uncaught exception (group=0x41f2ee30)
E/AndroidRuntime( 1370): FATAL EXCEPTION: main
E/AndroidRuntime( 1370): Process: com.google.process.gapps, PID: 1370
E/AndroidRuntime( 1370): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1370): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1370): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1370): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1370): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1370): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1370): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1370): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1370): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1370): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1370): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1370): 	... 10 more
E/ActivityManager(  916): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
D/Process ( 1370): killProcess, pid=1370
D/Process ( 1370): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  916): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5109 uid=10098 gids={50098, 3003, 5012}
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 1370
I/ActivityManager(  916): Process com.google.process.gapps (pid 1370) has died.
D/WifiService(  916): Client connection lost with reason: 4
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20826ms
I/DeviceManagement( 5109): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5109 dbg=false s=true
I/DeviceManagement( 5109): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5109): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5109): WorkflowService: Starting workflow service
I/DeviceManagement( 5109): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@423930b0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5109): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5109): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5109): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5109): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  916): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5123 uid=10099 gids={50099, 3003, 5012}
W/PackageManager(  916): Unable to load service info ResolveInfo{42c42530 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  916): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  916): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  916): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  916): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  916): 	at dalvik.system.NativeStart.main(Native Method)
I/DeviceManagement( 5109): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5109): SessionStateController: Checking invariants...

```
