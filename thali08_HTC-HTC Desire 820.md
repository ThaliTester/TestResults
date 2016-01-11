#### Test 5497026186051be_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42e4f2c8 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4411): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4411): ====startRecUseTime====
D/htc.customization.log.level( 4411):  is 
W/CustomizationLogLevel( 4411): Level value is invalid, use default level 2
D/CustomizationManager( 4411):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4411): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4411): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4411): Parsing tag category name = system
I/CustomizationCIDLoader( 4411): Parsing tag category name = application
I/CustomizationCIDLoader( 4411): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4411): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4411): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4411): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4411): Parsing tag category name = Settings
D/CustomizationManager( 4411):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4411):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4411): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4411): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4411): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4411): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4411
D/PMS     (  906): acquireHCC(426bd8e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42575b78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6c439fb8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1123650840
D/PMS     (  906): acquireWL(420b84b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e0f828
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4422 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4422): Copying FileAsset 0x5c7f0d40 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4422): Binding Chromium to main looper Looper (main, tid 1) {41c03480}
I/LibraryLoader( 4422): Expected native library version number "",actual native library version number ""
I/chromium( 4422): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4422): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42191c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(42147f40): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(42191c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420a8a18:true
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4422): 1103204504: getState(). Returning 12
I/Adreno-EGL( 4422): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4422): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4422): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4422): Local Branch: 
I/Adreno-EGL( 4422): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4422): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4422):                  aa63bbd948f41d15fc72f585e
W/chromium( 4422): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4422): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4422): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4422): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4422): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4422): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4422): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4422): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4422): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4422): CordovaWebView is running on device made by: HTC
,W/AwContents( 4422): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1271
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +294ms
W/ResourceType( 4422): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4422): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c4a748, mServedView=org.apache.cordova.engine.SystemWebView{41c103b0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4422): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=4422
D/PMS     (  906): releaseWL(420b84b8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4422): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4422): JniHelper::setJavaVM(0x417bf010), pthread_self() = 1663062856
D/JX-Cordova( 4422): jxcore cordova android initializing
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/dalvikvm-heap( 4422): Grow heap (frag case) to 11.582MB for 95956-byte allocation
I/dalvikvm-heap( 4422): Grow heap (frag case) to 11.661MB for 143930-byte allocation
I/dalvikvm-heap( 4422): Grow heap (frag case) to 11.776MB for 215890-byte allocation
I/dalvikvm-heap( 4422): Grow heap (frag case) to 11.951MB for 323830-byte allocation
I/dalvikvm-heap( 4422): Grow heap (frag case) to 12.223MB for 485740-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4422): Grow heap (frag case) to 13.223MB for 1092904-byte allocation
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/dalvikvm-heap( 4422): Grow heap (frag case) to 14.096MB for 1639352-byte allocation
,I/dalvikvm-heap( 4422): Grow heap (frag case) to 15.446MB for 2459024-byte allocation
,I/dalvikvm-heap( 4422): Grow heap (frag case) to 17.462MB for 3688532-byte allocation
,W/jxcore-log( 4422): Initializing JXcore engine
,W/jxcore-log( 4422): JXcore engine is ready
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(426bd8e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(42575b78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4422): Starting JXcore engine
,D/PMS     (  906): acquireWL(4216d9a8): PARTIAL_WAKE_LOCK  Icing 0x1 2233 10028 null
,D/PMS     (  906): releaseWL(4216d9a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(424de0f8): PARTIAL_WAKE_LOCK  Icing 0x1 2233 10028 null
,W/jxcore-log( 4422): Platform android
W/jxcore-log( 4422): 
,W/jxcore-log( 4422): Process ARCH arm
W/jxcore-log( 4422): 
,D/PMS     (  906): releaseWL(424de0f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/jxcore-log( 4422): JXcore Cordova bridge is ready!
I/jxcore-log( 4422): 
,W/jxcore-log( 4422): JXcore engine is started
,I/chromium( 4422): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4422): Toggling radios to true
I/jxcore-log( 4422): 
,D/BluetoothAdapter( 4422): enable(): BT is already enabled..!
,D/WifiManager( 4422): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1450
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
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
D/WifiService(  906): setWifiEnabled: true pid=4422, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
D/WifiService(  906): New client listening to asynchronous messages
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4422): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4422): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): TDLS: Tear down peers
I/wpa_supplicant( 1166): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4422): Radios toggled
I/jxcore-log( 4422): 
I/jxcore-log( 4422): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4422): 
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1166): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1166): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1166): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d79bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1166): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1166): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonito,r:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  906): acquireWL(44132540): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19246 mDataStallAlarmIntent=PendingIntent{4266de28: PendingIntentRecord{42693a68 android broadcastIntent}}
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/UsbnetStateTracker(  906): isAvailable+-
,D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): Fast associate: Old scan results
I/wpa_supplicant( 1166): wpa_supplicant_scan enter
I/wpa_supplicant( 1166): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1166): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1166): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1166): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1166): nl80211: Event message available
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/wpa_supplicant( 1166): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WISPrService( 4202): >>>>>WISPrService start isConnected = false<<<<<
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4202): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  365): [NET] entry_id:5   entry:0xb8bc5f78  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8bc9fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8bca108  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8bc6150  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8bca2e0  removed 
,D/libc    (  365): [NET] entry_id:1   entry:0xb8bca410  removed 
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
,D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(42782998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/PMS     (  906): acquireWL(425da5a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  906): acquireWL(4217de70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WISPrService( 4202): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  906): releaseWL(425da5a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1360/10028)
D/WISPrService( 4202): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  906): releaseWL(4217de70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): releaseWL(42782998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  906): releaseWL(42147f40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(426cfab8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1426/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1894/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4311/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3866): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3866/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4311/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4482 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42701ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{427340d0: PendingIntentRecord{4277f660 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452511748713, Int=60000
,D/PMS     (  906): releaseWL(42701ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2443/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4494 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/SMSBackup( 4482): SMSBackupAgentService started
D/SMSBackup( 4482): Checking restore status
,D/PMS     (  906): releaseWL(426cfab8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/SMSBackup( 4482): Restore complete
D/SMSBackup( 4482): cancelCheckAlarm
D/SMSBackup( 4482): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3615
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3615:com.htc.task/u0a70 (adj 15): empty #17
,D/ACRA    ( 4494): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4494): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4494): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4494): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4494): Preparing secondary program dexes.
V/DexLibLoader( 4494): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4494): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4494): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4494): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4494): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4494): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4494): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4494): Dex already copied
D/OdexVerifier( 4494): Odex verification is skipped.
V/DexLibLoader( 4494): Creating class loader
,V/DexLibLoader( 4494): Finished creating class loader
V/DexLibLoader( 4494): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4494): Dex already copied
D/OdexVerifier( 4494): Odex verification is skipped.
,V/DexLibLoader( 4494): Creating class loader
V/DexLibLoader( 4494): Finished creating class loader
V/DexLibLoader( 4494): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4494): Dex already copied
D/OdexVerifier( 4494): Odex verification is skipped.
V/DexLibLoader( 4494): Creating class loader
,V/DexLibLoader( 4494): Finished creating class loader
V/DexLibLoader( 4494): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4494): Dex already copied
D/OdexVerifier( 4494): Odex verification is skipped.
,V/DexLibLoader( 4494): Creating class loader
V/DexLibLoader( 4494): Finished creating class loader
,V/DexLibLoader( 4494): Verifying classes from secondary dexes.
,D/DexLibLoader( 4494): DexLibLoader.ensureDexLoaded took 16 ms,
,I/ActivityManager(  906): Recipient 3615
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4494): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1166): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1166): nl80211: Survey data missing
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1166): Sorted scan results
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1166): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1166): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1166): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-75
I/wpa_supplicant( 1166): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-87
D/wpa_supplicant( 1166): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1166): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1166): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1166): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1166): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1166): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1166): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1166): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1166): wpa_supplicant_pick_network+
I/wpa_supplicant( 1166): Selecting BSS from priority group 1
I/wpa_supplicant( 1166): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1166): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1166): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1166): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1166):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1166):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1166): Start print parameters
I/wpa_supplicant( 1166): wpa_s->wpa_state is 3
I/wpa_supplicant( 1166): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1166): isConcurrentMode() is 0
I/wpa_supplicant( 1166): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1166): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1166): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1166): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1166): wpa_s->reassociate is 1
I/wpa_supplicant( 1166): wpa_s->is_screen_on 1
I/wpa_supplicant( 1166): wpa_s->ifname wlan0
I/wpa_supplicant( 1166): End print parameters
I/wpa_supplicant( 1166): selected network = 1
D/wpa_supplicant( 1166): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d7b4e8  current_ssid=0x0
D/wpa_supplicant( 1166): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): supplicant attached completed, trigg,er assoc.
D/wpa_supplicant( 1166): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1166): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1166): check if in concurrent case
,I/wpa_supplicant( 1166): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1166): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 1166): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1166): RSN: PMKSA cache search - network_ctx=0xb8d7b4e8 try_opportunistic=0
D/wpa_supplicant( 1166): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1166): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1166): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1166): nl80211: Unsubscribe mgmt frames handle 0xb8d7a718 (mode change)
D/wpa_supplicant( 1166): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d7a718
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Register frame type=0xd0 nl_handle=0xb8d7a718
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1166): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1166):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1166):   * freq=2412
D/wpa_supplicant( 1166):   * Auth Type 0
,D/wpa_supplicant( 1166):   * WPA Versions 0x2
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1166): nl80211: Connect request send successfully
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1166): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1166): reply (636) for get BSS: id=0
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1166): freq=5220
I/wpa_supplicant( 1166): level=-47
I/wpa_supplicant( 1166): tsf=0000000104881182
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG7005g
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=1
I/wpa_supplicant( 1166): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-53
I/wpa_supplicant( 1166): tsf=0000000104881201
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=NG700
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=2
I/wpa_supplicant( 1166): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1166): freq=2452
I/wpa_supplicant( 1166): level=-75
I/wpa_supplicant( 1166): tsf=0000000104881206
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1166): ssid=Gonzos
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=3
I/wpa_supplicant( 1166): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): freq=2412
I/wpa_supplicant( 1166): level=-53
I/wpa_supplicant( 1166): tsf=0000000104881196
I/wpa_supplicant( 1166): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1166): ssid=01ABC
I/wpa_supplicant( 1166): ====
I/wpa_supplicant( 1166): id=4
I/wpa_supplicant( 1166): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1166): freq=2437
I/wpa_supplicant( 1166): level=-87
I/wpa_supplicant( 1166): tsf=0000000104881210
I/wpa_supplicant( 1166): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1166): ssid=UPC5999698
I/wpa_supplicant( 1166): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/dalvikvm( 4494): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104881182, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 104881201, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2452, timestamp: 104881206, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 104881196, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 104881210, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4494): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1166): nl80211: Event message available
D/wpa_supplicant( 1166): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1166): nl80211: Connect event
D/wpa_supplicant( 1166): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1166): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1166): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1166): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1166): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1166): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1166): TDLS: Remove peers on association
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1166): EAPOL: enable timer tick
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): Get randomness: len=32 entropy=6
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
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:getSSIDFromString i,d=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d7a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1166):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1166): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f66b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1166):    broadcast key
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1166): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1166): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1166): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1166): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1166): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1166): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1166): set send_ind_to_ndc = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1166): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1166): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1166): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1166): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1166): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1166): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1166): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1166): EAPOL authentication completed successfully
I/wpa_supplicant( 1166): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1166): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1166): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1166): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,E/FbInjectorInitializer( 4494): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 4202): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4202): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 1
I/wpa_supplicant( 1166): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43d7cae8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426c7090 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426c7090 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4494): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4494): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4494): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3171
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3171:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  906): acquireWL(43432a48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2233 10028 null
,I/ActivityManager(  906): Recipient 3171
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43c55e88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2233 10028 null
,D/PMS     (  906): releaseWL(43432a48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/PMS     (  906): releaseWL(43c55e88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4524 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,W/fb4a(:<default>):UserScope( 4494): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4494): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4494): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4524): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4524): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4541 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4252
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4252:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4494): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 4252
,E/dalvikvm( 4494): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4494): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4494): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4494): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4494): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4494): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4494): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4494): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4494): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4494): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4494): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4494): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4494): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4494): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4494): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4494): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/Process (  906): killProcessQuiet, pid=3848
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4573 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3848:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 9.962MB for 84664-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 10.002MB for 39954-byte allocation
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1166): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/ActivityManager(  906): Recipient 3848
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(43d7cae8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 10.079MB for 79892-byte allocation
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19248 delay=15s
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4202): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@42531448
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  906): syncGetConfiguredNetworks
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(435a3bf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=100 [1][1][0]
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): acquireWL(4309f1c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2233 10028 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
D/PMS     (  906): releaseWL(435a3bf8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(440239a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2233 10028 null
,D/PMS     (  906): releaseWL(4309f1c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
I/CheckinService( 2233): Preparing to send checkin request
I/EventLogService( 2233): Accumulating logs since 1452511699101
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4573/10151)
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,V/WebViewChromiumFactoryProvider( 4573): Binding Chromium to main looper Looper (main, tid 1) {41c08358}
,I/LibraryLoader( 4573): Expected native library version number "",actual native library version number ""
,I/chromium( 4573): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/GoogleHttpClient( 2233): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2233): Using GMS GoogleHttpClient
,I/BrowserStartupController( 4573): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 10.279MB for 75760-byte allocation
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/PMS     (  906): acquireWL(43ba3788): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4573): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43c883f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(43ba3788): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4415fde0 u0 ReceiverList{44132e78 4494 com.facebook.katana/10026/u0 remote:440ce9a0}}
,I/Adreno-EGL( 4573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4573): Local Branch: 
I/Adreno-EGL( 4573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4573):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4415fde0 u0 ReceiverList{44132e78 4494 com.facebook.katana/10026/u0 remote:440ce9a0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{435137d0 u0 ReceiverList{43404048 4494 com.facebook.katana/10026/u0 remote:43403f20}}
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2233/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2233/10028)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,I/NSApplication( 4573): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4573/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4573/10151)
,D/PMS     (  906): acquireWL(43d107b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
,D/PMS     (  906): releaseWL(43d107b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/GCoreFlp( 1426): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(4409c690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4177/10160)
D/PMS     (  906): releaseWL(4409c690): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4177/10160)
,D/Process (  906): killProcessQuiet, pid=4004
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4004:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/wpa_supplicant( 1166): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1166): EAPOL: disable timer tick
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2233): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{420dfad0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 7 16 12
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4634 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  906): Recipient 4004
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MultiDex( 4634): install
,I/MultiDex( 4634): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4634): loading existing secondary dex files
,I/MultiDex( 4634): load found 1 secondary dex files
,I/MultiDex( 4634): install done
,I/ProviderInstaller( 4634): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SensorManager(  906): mEventCount = 1050
,I/Adreno-EGL( 4634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4634): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4634): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4634): Local Branch: 
I/Adreno-EGL( 4634): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4634): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4634):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4634): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4634): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4634): Local Branch: 
I/Adreno-EGL( 4634): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4634): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4634):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(44132540): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/acms    ( 1894): Checking Certificates
I/acms    ( 1894): Checking Developer Certificates
I/acms    ( 1894): Checking Application Certificates
I/acms    ( 1894): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1894): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1894): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1894): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1894): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1894): Updating next query delay: 75600000
I/mlserverapp( 1894): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1894): cancelACMSProgrammedChecks
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1894/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1426/10028)
D/PMS     (  906): acquireWL(4403b8b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3866/10154)
I/NetworkMonitor( 3866): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4311/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4524/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3901/10051)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4311/10100)
D/PMS     (  906): acquireWL(43c5c1e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2443/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
D/PMS     (  906): releaseWL(43c5c1e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(4403b8b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4494): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4494): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/PMS     (  906): acquireWL(43d5c998): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2233 10028 null
,D/PMS     (  906): releaseWL(43d5c998): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1360): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  906): acquireWL(42451cc0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10028 null
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3288 +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4524): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4524): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1396): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1396): service - handleMessage() setting current location null
,D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4573/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4177/10160)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=50 [2][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4177/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,I/dalvikvm-heap( 4177): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  906): acquireWL(424c3ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  906): releaseWL(424c3ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4634): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4634): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4634): Local Branch: 
I/Adreno-EGL( 4634): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4634): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4634):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4634/10028)
,D/GCM     ( 1360): Connected
D/PMS     (  906): acquireWL(42612e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  906): releaseWL(42451cc0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  906): releaseWL(42612e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4276d4d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/GCM     ( 1360): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  906): acquireWL(42655cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  906): releaseWL(4276d4d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(42655cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4634): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 2233): Sending checkin request (9157 bytes)
D/libc    ( 2233): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2233): [NET] getaddrinfo-,err=8
D/libc    ( 2233): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2233): [NET] getaddrinfo-, 1
,D/libc    ( 2233): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c8b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 64
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2233): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2233): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2233): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=4 [25][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(4274f520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/PMS     (  906): releaseWL(4274f520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2233/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2233/10028)
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2233): awaiting user notification for token
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41bf80e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 7 4 12
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinTask( 2233): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2233): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(440239a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2233): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e18870 that was originally bound here
E/ActivityThread( 2233): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e18870 that was originally bound here
E/ActivityThread( 2233): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2233): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2233): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2233): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2233): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2233): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2233): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2233): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2233): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2233): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2233): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2233): 	at bks.a(SourceFile:298)
E/ActivityThread( 2233): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2233): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2233): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1360): GCM config loaded
W/fb4a(:<default>):UserScope( 4494): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4494): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4494): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =21d4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  906): releaseWL(43c883f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42203520
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42203520, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424449e0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@427584b8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 370ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44080800)
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
D/NfcService( 1256): applyRouting -2
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4422
,D/PMN     (  906): wakingUp
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): acquireWL(42a5e850): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/PMS     (  906): releaseWL(42a5e850): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/PMS     (  906): acquireWL(435181c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(435181c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2443): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1256): applyRouting - 0
,D/MtpService( 2443): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting -2
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): acquireWL(4401bde0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): releaseWL(4401bde0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19249 delay=15s
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/TetherSettings( 4202): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4202): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4202): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4202): Cust_ConnectToPC   : spcsc>false
D/        ( 4202): Cust_ConnectToPC   : IPT>true
,D/        ( 4202): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,W/Settings( 4202): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,E/SmartNS_Utility( 4202): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4202): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4202): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/PSReceiver( 4202): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,I/SmartNS_PSService( 4202): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,W/Settings( 4202): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4202):  defaultType:0
,D/WifiNative-wlan0(  906):    returned true
,I/ClockThread( 1116): stop update clock
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/NetworkPolicy(  906): updateScreenOn: false
,I/GAV2    ( 4573): Thread[GAThread,5,main]: No campaign data found.
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4683 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1789): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): onScreenOn: 1452511755718
D/PMS     (  906): acquireWL(436f0e10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(436f0e10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1789): onScreenOn: 1452511755718
,D/PMS     (  906): acquireWL(44083390): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4683 1000 null
D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424449e0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424449e0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@427584b8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(422cb858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/PMS     (  906): releaseWL(44083390): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19249 mDataStallAlarmIntent=PendingIntent{43763360: PendingIntentRecord{42693a68 android broadcastIntent}}
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/PMS     (  906): acquireWL(438febc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4281
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  906): updateScreenOn: false
,I/ActivityManager(  906): Killing 4281:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): releaseWL(438febc0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  906): Recipient 4281
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
,W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427584b8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427584b8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427584b8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427584b8
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427588b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427588b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
D/AutoSetting( 1396): service - mHandler: cancel location update
D/AutoSetting( 1396): service -           changes count: 0
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  906): acquireWL(4303cf00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1789): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1789): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1789): onScreenOff
D/PMS     (  906): releaseWL(4303cf00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  906): acquireWL(4342dd00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
,D/PMS     (  906): acquireWL(43434fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
,D/PMS     (  906): releaseWL(4342dd00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43434fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{41df6ed8 u0 com.test.thalitest/.MainActivity t2}
,I/jxcore-log( 4422): Test app app.js loaded
I/jxcore-log( 4422): 
,I/Choreographer( 4422): Skipped 533 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4422): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4422): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4422): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41c103b0 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  906): releaseWL(422cb858): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  906): killProcessQuiet, pid=4311
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4311:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4311
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4334
,I/ActivityManager(  906): Killing 4334:com.htc.backup/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1465): service - handleMessage() quit looper
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4334
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 10.967MB for 24676-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 10.986MB for 37010-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.015MB for 55510-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4494/10026)
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.108MB for 82850-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.108MB for 55238-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.115MB for 55792-byte allocation
,D/libc    ( 4494): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4494): [NET] getaddrinfo-,err=8
D/libc    ( 4494): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4494): [NET] getaddrinfo-, 1
,D/libc    ( 4494): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =68a4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 44
D/libc    (  365): [NET]res_nsend:resplen=93
D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4494): [NET] getaddrinfo_proxy-, success
I/global  ( 4494): call createSocket() return a new socket.
D/libc    ( 4494): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4494): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4494): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4494): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(436acbf0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4494 10026 null,
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4494): I/O error closing connection
I/global  ( 4494): java.net.SocketException: Socket is closed
I/global  ( 4494): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4494): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4494): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4494): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4494): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4494): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4494): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4494): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4494): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4494): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4494): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4494): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4494): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4494): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4494): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4494): Removing a connection that never existed!
D/PMS     (  906): releaseWL(436acbf0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43daf9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43daf9d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(439961b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(439961b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1465): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/DotMatrix( 1564): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1465): service - mHandler: update timezone
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1465): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1465): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41d3c2f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  906): acquireWL(43652a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42562790: PendingIntentRecord{42562758 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140787, Int=0
,D/AutoSetting( 1396): service - handleMessage() stop self
V/AlarmManager(  906): sending alarm PendingIntent{432aab18: PendingIntentRecord{4255ef00 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140954, Int=0
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(44128158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  906): acquireWL(43cdd930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  906): releaseWL(43652a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d2e1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(43cdd930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  906): killProcessQuiet, pid=3901
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3901:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3901
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(44128158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42e2aa68 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(43c562f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e53c0: PendingIntentRecord{421a81a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155101, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c562f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/AutoSetting( 1465): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4298
,I/ActivityManager(  906): Killing 4298:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4298
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(44404318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44404318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(443479c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e53c0: PendingIntentRecord{421a81a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215102, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(443479c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44326e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{426c0c30: PendingIntentRecord{4394e8b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=225919, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4722 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42674eb0: PendingIntentRecord{42694f68 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452511864999, Int=10800000
,D/PMS     (  906): releaseWL(44326e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4722/10047)
,D/Process (  906): killProcessQuiet, pid=4352
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4352:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4352
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2233/10028)
,D/PMS     (  906): acquireWL(44030498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{44028c50: PendingIntentRecord{4394e8b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230856, Int=0
,D/PMS     (  906): releaseWL(44030498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(44017a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44017a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43d97330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e53c0: PendingIntentRecord{421a81a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275102, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d97330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4422): --= Surplus to requirements =--
I/jxcore-log( 4422): 
I/jxcore-log( 4422): ****TEST TOOK:  ms ****
I/jxcore-log( 4422): 
,I/jxcore-log( 4422): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4422): 
,E/cutils-trace( 4743): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4743): ====startRecUseTime====
D/htc.customization.log.level( 4743):  is 
,W/CustomizationLogLevel( 4743): Level value is invalid, use default level 2
,D/CustomizationManager( 4743):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4743): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4743): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4743): Parsing tag category name = system
,I/CustomizationCIDLoader( 4743): Parsing tag category name = application
I/CustomizationCIDLoader( 4743): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4743): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4743): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4743): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4743): Parsing tag category name = Settings
D/CustomizationManager( 4743):  Read CID file spent 0.105 (s)
,D/CustomizationManager( 4743):  All configurations done spent 0.105 (s),
W/HtcNativeFlag( 4743): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4743): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4743): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4743): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4743, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4422
,I/ActivityManager(  906): Killing 4422:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906):   Force finishing activity ActivityRecord{41df6ed8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x644e0608 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  906): Skipping PackageSetting{4232f1c0 com.example.hello/10356} due to missing metadata
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4422 uid 10348
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,I/dalvikvm-heap( 4177): Grow heap (frag case) to 15.196MB for 1821008-byte allocation
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
W/InputDispatcher(  906): channel '42594188 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '42594188 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1894): Unregistering com.test.thalitest
E/acms    ( 1894): Could not unregister removed application com.test.thalitest
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42594188 com.test.thalitest.MainActivity (s)'
,W/GeofencerStateMachine( 1426): Ignoring removeGeofence because network location is disabled.
I/WindowState(  906): WIN DEATH: Window{42594188 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PMS     (  906): acquireWL(426454a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(426454a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/WindowManager(  906): WINDOW DIED Window{42594188 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,D/PackageBroadcastService( 2233): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4758 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/MultiDex( 4758): install
,I/PackageManager(  906):   Scheme: "smsto"
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/MultiDex( 4758): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  906): Delaying start of: ServiceRecord{43cb0ca0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
,I/MultiDex( 4758): loading existing secondary dex files
,I/MultiDex( 4758): load found 1 secondary dex files
,I/MultiDex( 4758): install done
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4774 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 2233): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2233, uid=10028, userID:0
,I/ProviderInstaller( 4758): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/PMS     (  906): acquireWL(42637980): PARTIAL_WAKE_LOCK  Icing 0x1 2233 10028 null
I/Icing   ( 2233): doRemovePackageData com.test.thalitest
,D/PMS     (  906): releaseWL(42637980): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/MultiDex( 4774): install
,I/MultiDex( 4774): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4774): loading existing secondary dex files
I/MultiDex( 4774): load found 1 secondary dex files
I/MultiDex( 4774): install done
,I/ProviderInstaller( 4774): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4369
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4369:com.htc.calendar/u0a13 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Recipient 4369
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2887): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4794 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,W/PackageManager(  906): Unable to load service info ResolveInfo{41c2fff8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  906): acquireWL(437f81e8): PARTIAL_WAKE_LOCK  Icing 0x1 2233 10028 null
,E/SQLiteLog( 2887): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2887): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63b36008
,E/IcingCorporaProvider( 2887): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2887): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2887): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2887): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2887): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2887): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2887): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2887): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2887): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2887): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2887): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2887): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2887): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2887): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2887): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2887): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2887): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2887): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2887): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2887): 	... 15 more
W/IcingCorporaProvider( 2887): notifyTableChanged failed.
W/IcingCorporaProvider( 2887): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2887): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
,E/SQLiteLog( 4758): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4758): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cab7dd8
,E/DriveAsyncService( 4758): disk I/O error (code 3850)
E/DriveAsyncService( 4758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4758): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4758): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4758): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4758): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4758): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  906): releaseWL(437f81e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteLog( 4758): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4758): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cab7dd8
,E/DocListDatabase( 4758): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4758): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4758): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4758): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4758): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4758): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4758): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4758): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4758): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4758): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4758): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4758): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4758): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4758): threadid=1: thread exiting with uncaught exception (group=0x417d0e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4758): FATAL EXCEPTION: main
E/AndroidRuntime( 4758): Process: com.google.android.gms.drive, PID: 4758
E/AndroidRuntime( 4758): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4758): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4758): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4758): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4758): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4758): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4758): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4758): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4758): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4758): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4758): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4758): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4758): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4758): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4758): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4758): 	... 10 more
,D/Process ( 4758): killProcess, pid=4758
,D/Process ( 4758): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4794): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4794): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4794): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4794): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4794): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4794): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4794): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4794): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4794): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4794): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4794): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4794): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4794): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4794): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4794): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4794): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4794): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4794): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4794): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4794): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4794): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4794): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4794): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4794): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4794): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4794): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4794): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4794): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4794): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4794): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4794): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4794): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4794): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4794): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4794): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4794): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4794): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4794): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4794): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4794): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4794): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4794): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4794): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4794): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4794): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4794): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4794): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4794): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4794): Opened ClientFlag.db in read-only mode
I/ActivityManager(  906): Recipient 4758
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4758) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
E/SQLiteDatabase( 4794): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4794): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4794): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4794): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4794): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4794): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4794): threadid=11: thread exiting with uncaught exception (group=0x417d0e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4794): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4794): Process: com.google.android.apps.docs, PID: 4794
E/AndroidRuntime( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4794): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4794): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4794): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4794): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4794): 	at aho.run(AbstractDatabaseInstance.java:455)
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
,D/Process ( 4794): killProcess, pid=4794
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4816 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4794): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4794
,D/Process (  906): killProcessQuiet, pid=4383
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4383:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4794) has died.
,I/ActivityManager(  906): Recipient 4383
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4816): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4816): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4816): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4816): threadid=10: thread exiting with uncaught exception (group=0x417d0e30)
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4816): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4816): Process: com.android.keychain, PID: 4816
E/AndroidRuntime( 4816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4816): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4816): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4816): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4816): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4829 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452511956425.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/PMS     (  906): acquireWL(425878a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/Process ( 4816): killProcess, pid=4816
,D/Process ( 4816): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425878a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/ActivityManager(  906): Recipient 4816
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4816) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10759ms
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/AppTag  ( 4829): getInstance(Context context)
,D/AppTag  ( 4829): getInstance(Context context)
,D/AppTag  ( 4829): onCreate()
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e39990): PARTIAL_WAKE_LOCK  AsyncService 0x1 4177 10160 null
,I/dalvikvm-heap( 4177): Grow heap (frag case) to 16.935MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(42e39990): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4848 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4848): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4848 dbg=false s=true
,I/DeviceManagement( 4848): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4848): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4848): WorkflowService: Starting workflow service
I/DeviceManagement( 4848): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c352f8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4848): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4848): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4848): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4848): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4862 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4848): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4848): SessionStateController: Checking invariants...
,D/Documents( 4862): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4862): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4862): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4862): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4862): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4862): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4862): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4862): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4862): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4862): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4862): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4862): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4862): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4862): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4862): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4862): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4862): threadid=1: thread exiting with uncaught exception (group=0x417d0e30)
,D/Process (  906): killProcessQuiet, pid=4482
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/AndroidRuntime( 4862): FATAL EXCEPTION: main
E/AndroidRuntime( 4862): Process: com.android.documentsui, PID: 4862
E/AndroidRuntime( 4862): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4862): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4862): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4862): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4862): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4862): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4862): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4862): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4862): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4862): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4862): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4862): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4862): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4862): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4862): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4862): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4862): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4862): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4862): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4862): 	... 10 more
I/ActivityManager(  906): Killing 4482:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
E/ActivityManager(  906): App crashed! Process: com.android.documentsui
,D/Documents( 4862): Loading roots for com.android.externalstorage.documents
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Recipient 4482
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452511956721.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4877 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  906): killProcessQuiet, pid=3866
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
,D/Process ( 4862): killProcess, pid=4862
,D/Process ( 4862): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Killing 3866:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4862
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.android.documentsui (pid 4862) has died.
,E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4848): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4848): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4848): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4848): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4848): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4848): 	at java.lang.Thread.run(Thread.java:864)
,D/ExternalStorage( 4877): After updating volumes, found 1 active roots
,I/DeviceManagement( 4848): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4848): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4848): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4848): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4848): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4848): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4848): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4848): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4848): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4848): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4892 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
W/DeviceManagement( 4848): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c352f8]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4848): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4848): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4848): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4848): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4848): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4848): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4848): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4848): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4848): WorkflowService: Stopping workflow service
,I/ActivityManager(  906): Recipient 3866
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.music (pid 3866): Died!
,E/SQLiteDatabase( 4892): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4892): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4892): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4892): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4892): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4892): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4892): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4892): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4892): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4892): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4892): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4892): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4892): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4892): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4892): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4892): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4892): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4892): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4892): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4892): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4892): Opened MyDB.db in read-only mode
,I/ActivityManager(  906): Killing 4524:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4524
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4524
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41c93cf8 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,D/PMS     (  906): acquireWL(4409c098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4409c098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null

```
