#### Test 55613145c131883_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
,--------- beginning of /dev/log/system
D/WIFI_ICON( 1111): WifiActivity: 0
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/cutils-trace( 4403): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4403): ====startRecUseTime====
D/htc.customization.log.level( 4403):  is 
W/CustomizationLogLevel( 4403): Level value is invalid, use default level 2
D/CustomizationManager( 4403):  Read ACC file spent 0.063 (s)
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
D/CustomizationManager( 4403):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4403):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4403): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4403): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1136889336
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4403
D/PMS     (  903): acquireHCC(43676230): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(4366aa48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/FeedHostManager( 1266): [onPause]
I/FeedProviderManager( 1266): onPause
I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bd4790
I/SocialFeedProvider( 1266): +onPause
I/SocialFeedProvider( 1266): -onPause
D/PMS     (  903): acquireWL(42e442f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4414 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1266): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4414): Binding Chromium to main looper Looper (main, tid 1) {41b19a68}
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
I/chromium( 4414): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4414): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(43581848): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435850b0:true
D/BluetoothAdapter( 4414): 1102257824: getState(). Returning 12
D/PMS     (  903): acquireWL(4357d9e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(4357d9e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4414): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4414): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4414): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4414): Local Branch: 
I/Adreno-EGL( 4414): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4414): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4414):                  aa63bbd948f41d15fc72f585e
W/chromium( 4414): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4414): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4414): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4414): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4414): CordovaWebView is running on device made by: HTC
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1266
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b63590, mServedView=org.apache.cordova.engine.SystemWebView{41b291b8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1202): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1202): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1202): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1202): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Enable input method client, pid=4414
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +300ms
,D/PMS     (  903): releaseWL(42e442f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WIFI_ICON( 1111): WifiActivity: 1
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/JsMessageQueue( 4414): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4414): JniHelper::setJavaVM(0x415f3048), pthread_self() = 1663207520
,D/JX-Cordova( 4414): jxcore cordova android initializing
,D/PMS     (  903): acquireWL(434c5c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=87 rxSum=71} preTxRxSum={txSum=85 rxSum=69}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  903): onDataStallAlarm: tag=20260 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20261 delay=15s
V/AlarmManager(  903): sending alarm PendingIntent{439115d8: PendingIntentRecord{42094b50 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100420, Int=0
D/PMS     (  903): releaseWL(434c5c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  903): mEventCount = 1200
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.538MB for 63974-byte allocation
,W/PluginManager( 4414): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.591MB for 95956-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.670MB for 143930-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.788MB for 215890-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.955MB for 323830-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.629MB for 728606-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 13.227MB for 1092904-byte allocation
,W/PluginManager( 4414): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 14.133MB for 1639352-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 15.458MB for 2459024-byte allocation
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(43676230): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(4366aa48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true,
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 17.456MB for 3688532-byte allocation
,W/jxcore-log( 4414): Initializing JXcore engine
,W/jxcore-log( 4414): JXcore engine is ready
,W/jxcore-log( 4414): Starting JXcore engine
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
,W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,D/PMS     (  903): releaseWL(43581848): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,I/chromium( 4414): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1111): WifiActivity: 0
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4414): Toggling radios to true
I/jxcore-log( 4414): 
,D/BluetoothAdapter( 4414): enable(): BT is already enabled..!
,D/WifiManager( 4414): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4414, uid=10189
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1201
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
D/WifiManager( 4414): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
D/WifiManager( 4414): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): TDLS: Tear down peers
I/wpa_supplicant( 1171): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4414): Radios toggled
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): My device name is: HTC-HTC Desire 820,
I/jxcore-log( 4414): 
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 48,
I/wpa_supplicant( 1171): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1171): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/wpa_supplicant( 1171): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb877abc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1171):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1171): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1171): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
,D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1171): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1171): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/WifiNative-wlan0(  903):    returned true
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiPerfLock(  903): release()
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(42d8af10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
,D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1171): Fast associate: Old scan results
I/wpa_supplicant( 1171): wpa_supplicant_scan enter
I/wpa_supplicant( 1171): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1171): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1171): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20261 mDataStallAlarmIntent=PendingIntent{434b3e30: PendingIntentRecord{42094b50 android broadcastIntent}}
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1171): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  903): Exit handleNetworkDisconnect
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4353): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4353): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4353): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4353): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  903): New client listening to asynchronous messages
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/libc    (  364): [NET] entry_id:6   entry:0xb8de6818  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8de6718  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb8de6028  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8de62f0  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8de6108  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb8de5e80  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8de61d0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8de6410  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb8de6588  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/PMS     (  903): acquireWL(42c11f98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(42a86b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  903): acquireWL(42a4c060): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1367/10028)
D/PMS     (  903): releaseWL(42a86b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiNative-wlan0(  903):    returned false
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  903): releaseWL(42a4c060): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  903): releaseWL(42c11f98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4467 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/PMS     (  903): acquireWL(43733dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
,I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1864/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
D/PMS     (  903): releaseWL(43733dd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/MusicStore( 4467): Database version: 95
,W/ContextImpl( 4467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4467, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 4467): Registered
,I/MediaRouter( 4467): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4467/10154)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2763/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4487 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4467): getSelectedRoute
,I/NetworkMonitor( 4467): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4467/10154)
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4467, uid=10154, userID:0
,D/Process (  903): killProcessQuiet, pid=3825
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4487): ACRA is enabled for com.facebook.katana, intializing...
I/ActivityManager(  903): Killing 3825:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/ACRA    ( 4487): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4487): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4487): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4487): Preparing secondary program dexes.
V/DexLibLoader( 4487): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4487): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4487): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4487): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4487): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4487): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4487): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4487): Creating class loader
,V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4487): Creating class loader
V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4487): Creating class loader
V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4487): Dex already copied
D/OdexVerifier( 4487): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4487): Creating class loader
V/DexLibLoader( 4487): Finished creating class loader
V/DexLibLoader( 4487): Verifying classes from secondary dexes.
,D/DexLibLoader( 4487): DexLibLoader.ensureDexLoaded took 15 ms
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3825
,W/dalvikvm( 4487): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1171): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1171): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1171): nl80211: Survey data missing
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1171): Sorted scan results
I/wpa_supplicant( 1171): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1171): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1171): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1171): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-75
I/wpa_supplicant( 1171): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1171): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1171): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1171): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1171): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1171): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1171): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1171): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1171): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1171): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1171): wpa_supplicant_pick_network+
I/wpa_supplicant( 1171): Selecting BSS from priority group 1
I/wpa_supplicant( 1171): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1171): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1171): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1171): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1171):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1171):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1171): Start print parameters
I/wpa_supplicant( 1171): wpa_s->wpa_state is 3
I/wpa_supplicant( 1171): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1171): isConcurrentMode() is 0
I/wpa_supplicant( 1171): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1171): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1171): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1171): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1171): wpa_s->reassociate is 1
I/wpa_supplicant( 1171): wpa_s->is_screen_on 1
I/wpa_supplicant( 1171): wpa_s->ifname wlan0
I/wpa_supplicant( 1171): End print parameters
I/wpa_supplicant( 1171): selected network = 1
D/wpa_supplicant( 1171): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb877c4e8  current_ssid=0x0
D/wpa_supplicant( 1171): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): supplicant attached completed, trigg,er assoc.
D/wpa_supplicant( 1171): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1171): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1171): check if in concurrent case
I/wpa_supplicant( 1171): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1171): RSN: PMKSA cache search - network_ctx=0xb877c4e8 try_opportunistic=0
D/wpa_supplicant( 1171): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1171): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1171): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1171): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1171): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1171): nl80211: Unsubscribe mgmt frames handle 0xb877b718 (mode change)
D/wpa_supplicant( 1171): nl80211: Subscribe to mgmt frames with non-AP handle 0xb877b718
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb877b718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1171):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1171):   * freq=2412
,D/wpa_supplicant( 1171):   * Auth Type 0
D/wpa_supplicant( 1171):   * WPA Versions 0x2
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1171): nl80211: Connect request send successfully
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  903): getDiscoveryDongleList
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1171): reply (636) for get BSS: id=0
I/wpa_supplicant( 1171): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1171): freq=5220
I/wpa_supplicant( 1171): level=-54
I/wpa_supplicant( 1171): tsf=0000000105171334
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1171): ssid=NG7005g
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=1
I/wpa_supplicant( 1171): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): freq=2412
I/wpa_supplicant( 1171): level=-50
I/wpa_supplicant( 1171): tsf=0000000105171330
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1171): ssid=NG700
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=2
I/wpa_supplicant( 1171): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1171): freq=2452
I/wpa_supplicant( 1171): level=-75
I/wpa_supplicant( 1171): tsf=0000000105171340
I/wpa_supplicant( 1171): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1171): ssid=Gonzos
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=3
I/wpa_supplicant( 1171): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): freq=2412
I/wpa_supplicant( 1171): level=-50
I/wpa_supplicant( 1171): tsf=0000000105171318
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1171): ssid=01ABC
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=4
I/wpa_supplicant( 1171): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1171): freq=2437
I/wpa_supplicant( 1171): level=-91
I/wpa_supplicant( 1171): tsf=0000000105171343
I/wpa_supplicant( 1171): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1171): ssid=UPC4688432
I/wpa_supplicant( 1171): ####
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 5220, timestamp: 105171334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 105171330, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2452, timestamp: 105171340, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 105171318, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 105171343, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1171): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
,D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1171): nl80211: Connect event
D/wpa_supplicant( 1171): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1171): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1171): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1171): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1171): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1171): TDLS: Remove peers on association
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1171): EAPOL: enable timer tick
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1171): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1171): Get randomness: len=32 entropy=6
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  903): Associated
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 1171): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb877b9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1171):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1171): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fbfb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1171):    broadcast key
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,E/wpa_supplicant( 1171): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 1171): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1171): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1171): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): set send_ind_to_ndc = 0
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1171): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1171): EAPOL authentication completed successfully
I/wpa_supplicant( 1171): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...,
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c6868
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c6868, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42369ab0
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@4239c3d0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false),
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/PMS     (  903): Going to sleep due to screen timeout...
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
V/LightsService(  903): setLight #2: color=#0
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/PMS     (  903): mWirelessDisplayManager is null
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 4353): >>>>>WISPrService start isConnected = false<<<<<
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WISPrService( 4353): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 1
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(43ff4af0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425a7260 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425a7260 target=com.android.internal.util.StateMachine$SmHandler }
,W/dalvikvm( 4487): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4487): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4487): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 366ms
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
W/fb4a(:<default>):StaticBindingVerifier( 4487): Verify
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42499b20)
,D/NfcService( 1251): ScreenObserver: OFF
,D/NfcService( 1251): applyRouting - 0
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=4414
D/PMN     (  903): wakingUp
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
,D/NfcService( 1251): applyRouting -2
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/PMS     (  903): acquireWL(42537790): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): releaseWL(42537790): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MtpService( 2763): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1251): applyRouting - 0
,D/MtpService( 2763): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting -2
D/PMN     (  903): onScreenOn
D/PMS     (  903): acquireWL(42e93f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42e93f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  903): acquireWL(424e4760): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  903): releaseWL(424e4760): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
,D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/ClockThread( 1111): stop update clock
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:On
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/NetworkPolicy(  903): updateScreenOn: false
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): acquireWL(440dd690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1798): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): onScreenOn: 1452773865512
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1798): onScreenOn: 1452773865512
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42369ab0
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42369ab0, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@4239c3d0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  903): releaseWL(440dd690): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(42629700): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20262 mDataStallAlarmIntent=null
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:Off
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1171): get_ip_address source addr = 02000000
I/wpa_supplicant( 1171): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  903):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  903): acquireWL(42550f90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/PMS     (  903): releaseWL(42550f90): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiService(  903): New client listening to asynchronous messages
D/NetworkPolicy(  903): updateScreenOn: false
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/ContactMessageStore( 1234): start background delete task...
D/ContactMessageStore( 1234): size: 0 , 0
,D/ContactMessageStore( 1234): Background delete complete
,W/fb4a(:<default>):BaseAnalyticsConfig( 4487): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4487): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/AutoSetting( 1401): service - mHandler: cancel location update
,D/AutoSetting( 1401): service -           changes count: 0
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(435c44f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
D/PMS     (  903): releaseWL(435c44f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1798): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1798): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1798): onScreenOff
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=4200
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4200:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4200
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(43634ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,D/PMS     (  903): acquireWL(4247c6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(43634ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/PMS     (  903): releaseWL(4247c6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/AutoSetting( 1401): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4527 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
,D/AutoSetting( 1401): Util - no network available!
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1401): service - mHandler: cancel location update
,D/AutoSetting( 1401): service -           changes count: 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4487): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4527): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4527): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4527): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4527): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4541 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4225
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4225:com.htc.calendar/u0a13 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4527/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4527/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4527/10078)
I/ActivityManager(  903): Recipient 4225
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4555 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4242
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4242:com.android.settings:remote/1000 (adj 15): empty #17
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,D/wpa_supplicant( 1171): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1171): EAPOL: disable timer tick
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4555): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4555): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 4487): Grow heap (frag case) to 9.967MB for 28144-byte allocation
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4487): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
W/GAV2    ( 4555): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4487): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4487): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4487): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4487): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4487): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4487): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/ContextImpl( 4555): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/dalvikvm( 4487): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4487): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4487): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4487): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4487): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4487): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4487): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4555): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  903): Recipient 4242
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.044MB for 39954-byte allocation
W/ActivityManager(  903): Activity pause timeout for ActivityRecord{42e42dd8 u0 com.test.thalitest/.MainActivity t2}
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.121MB for 79892-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4555/10151)
,V/WebViewChromiumFactoryProvider( 4555): Binding Chromium to main looper Looper (main, tid 1) {41b21230}
,I/LibraryLoader( 4555): Expected native library version number "",actual native library version number ""
,I/chromium( 4555): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4555): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(440ed3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  903): acquireWL(424e7a90): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4555): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(440ed3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4555): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4555): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4555): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4555): Local Branch: 
I/Adreno-EGL( 4555): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4555): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4555):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4555): Starting up...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4555/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4555/10151)
,I/dalvikvm-heap( 4487): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/Process (  903): killProcessQuiet, pid=4051
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4026/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4026/10160)
,I/ActivityManager(  903): Killing 4051:com.google.android.gm/u0a107 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43544530 u0 ReceiverList{435263a8 4487 com.facebook.katana/10026/u0 remote:434bf920}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43544530 u0 ReceiverList{435263a8 4487 com.facebook.katana/10026/u0 remote:434bf920}}
,D/AutoSetting( 1401): receiver - intent: android.intent.action.USER_PRESENT
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c1c590 u0 ReceiverList{43c0e3e8 4487 com.facebook.katana/10026/u0 remote:43c0d288}}
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 4353): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4353): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4353): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4353): Cust_ConnectToPC   : spcsc>false
D/        ( 4353): Cust_ConnectToPC   : IPT>true
,D/        ( 4353): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4353): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4353): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4353): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4353): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4353): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4353): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4353): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4353):  defaultType:0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,I/ActivityManager(  903): Recipient 4051
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4597 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/GCoreFlp( 1417): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(435953f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
D/PMS     (  903): releaseWL(435953f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ContextImpl( 4597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4597): isEpsOn(), nState = 0
,D/PMS     (  903): acquireWL(44008238): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4597 1000 null
,D/PMS     (  903): releaseWL(44008238): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4597): getMobilePolicyEnabled, result = true
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/Process (  903): killProcessQuiet, pid=4174
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system,
,W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ActivityManager(  903): Killing 4174:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4487): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4597): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4597): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4597): isEpsOn(), nState = 0,
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4239c3d0
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4239c3d0, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4239c3d0, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4239c3d0
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42393ad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42393ad8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  903): Recipient 4174
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(4321b088): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
,D/PMS     (  903): acquireWL(432d1950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
,D/PMS     (  903): releaseWL(4321b088): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  903): releaseWL(432d1950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/WifiP2pService(  903): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43ff4af0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1171): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  903): WAN detection
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4244b9f8
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4353): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(43375c68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4527/10078)
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
D/PMS     (  903): acquireWL(43c43478): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  903): acquireWL(4402ec40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
D/PMS     (  903): releaseWL(43c43478): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 1217): Preparing to send checkin request
,I/EventLogService( 1217): Accumulating logs since 1452773808339
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
I/GoogleHttpClient( 1217): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1217): Using GMS GoogleHttpClient
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43375c68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1217): awaiting user notification for token
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41bab950 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 6 2 12
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4651 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4651): install
,I/MultiDex( 4651): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4651): loading existing secondary dex files
,I/MultiDex( 4651): load found 1 secondary dex files
,I/MultiDex( 4651): install done
,I/ProviderInstaller( 4651): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4651): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4651/10028)
,I/Adreno-EGL( 4651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4651): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4651): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4651): Local Branch: 
I/Adreno-EGL( 4651): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4651): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4651):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4651): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4651): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4651): Local Branch: 
I/Adreno-EGL( 4651): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4651): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4651):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4651): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4651): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4651): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4651): Local Branch: 
I/Adreno-EGL( 4651): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4651): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4651):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  903): releaseWL(42d8af10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/PMS     (  903): acquireWL(440bf458): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(440bf458): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CaptivePortalTracker(  903): NoActiveNetworkState
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43feef40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1864/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1864): Checking Certificates
I/acms    ( 1864): Checking Developer Certificates
I/acms    ( 1864): Checking Application Certificates
I/acms    ( 1864): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1864): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1864): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1864): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1864): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1864): Updating next query delay: 75600000
I/mlserverapp( 1864): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1864): cancelACMSProgrammedChecks
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3866/10051)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4467/10154)
,I/NetworkMonitor( 4467): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4527/10078)
D/PMS     (  903): acquireWL(435c1010): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ActivityManager(  903): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4672 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  903): releaseWL(43feef40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4296/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
E/ExternalAccountType( 1325): Unsupported attribute readOnly
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2763/10021)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/PMS     (  903): acquireWL(42e3ddd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
D/PMS     (  903): releaseWL(42e3ddd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a266 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  903): acquireWL(424e0c90): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10028 null
,D/AutoSetting( 1401): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4527): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4527): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
,D/AutoSetting( 1401): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1401): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1401): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4555/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4026/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4026/10160)
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1825/10178)
,I/dalvikvm-heap( 4026): Grow heap (frag case) to 13.515MB for 1821008-byte allocation
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,I/NewsWeather( 4672): LocationClient connecting
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  903): acquireWL(440d3bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  903): releaseWL(440d3bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4672): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4672): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4672): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4672): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4672): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4672): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/CheckinTask( 1217): Sending checkin request (9012 bytes)
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1217): [NET] getaddrinfo-,err=8
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1217): [NET] getaddrinfo-, 1
,D/libc    ( 1217): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c8fd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 103
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1217): [NET] getaddrinfo_proxy-, success,
,I/ProviderInstaller( 4672): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42534cc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/NewsWeather( 4672): onConnected null
,D/GCM     ( 1367): Connected
D/PMS     (  903): acquireWL(424fab30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/PMS     (  903): releaseWL(42534cc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1217): [NET] getaddrinfo-,err=8
I/NewsWeather( 4672): Last usage 0, idle 1452773868s, sync interval 2592000s
,I/NewsWeather( 4672): setPeriodicSync in seconds 2592000
,W/GCoreFlp( 1417): No location to return for getLastLocation()
,I/NewsWeather( 4672): LocationClient onConnected: location null
D/PMS     (  903): releaseWL(424e0c90): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/PMS     (  903): acquireWL(420939f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/PMS     (  903): acquireWL(41ff74c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1417 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028),
D/PMS     (  903): releaseWL(420939f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  903): releaseWL(424fab30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(41c96cb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
,D/PMS     (  903): releaseWL(41ff74c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
,I/NewsWeather( 4672): Skip sync for lookup editions
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
,I/NewsWeather( 4672): syncNewsAppData traffic type BACKGROUND_POLL
,D/GCM     ( 1367): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  903): releaseWL(41c96cb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/NewsWeather( 4672): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/PMS     (  903): acquireWL(43fe0d68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  903): releaseWL(43fe0d68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4672): Unrecoverable authentication exception
E/NewsWeather( 4672): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c6e720 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 6 2 12
D/libc    ( 4672): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4672): [NET] getaddrinfo-,err=8
D/libc    ( 4672): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4672): [NET] getaddrinfo-, 1
,D/libc    ( 4672): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =61e8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4672): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4672): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4672): [NET] getaddrinfo-,err=8
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/AutoSetting( 1495): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3609
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 3609:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3609
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4487): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=17 [29][5][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/fb4a(:<default>):LocalFbBroadcastManager( 4487): Called registerBroadcastReceiver twice.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42e665c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  903): releaseWL(42e665c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/PMS     (  903): acquireWL(444348a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
E/NewsWeather( 4672): Failed to syncNewsAppData
E/NewsWeather( 4672): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1217): awaiting user notification for token
,I/RemoteViews( 1111): com.google.android.gms (false,0)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/PMS     (  903): releaseWL(444348a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41ecb708 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 6 2 12
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 66066, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(44380800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/PMS     (  903): releaseWL(435c1010): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/Process (  903): killProcessQuiet, pid=4266
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  903): Killing 4266:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  903): releaseWL(44380800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4321b290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/PMS     (  903): releaseWL(4321b290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  903): Recipient 4266
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4487/10026)
I/CheckinTask( 1217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1217): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
D/PMS     (  903): acquireWL(43aabab8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4467 10154 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,W/ContextImpl( 4467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  903): releaseWL(4402ec40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1217): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b23d10 that was originally bound here
E/ActivityThread( 1217): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b23d10 that was originally bound here
E/ActivityThread( 1217): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1217): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1217): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1217): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1217): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1217): ,	at xs.<init>(SourceFile:175)
E/ActivityThread( 1217): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1217): 	at bks.a(SourceFile:298)
E/ActivityThread( 1217): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1217): 	at java.lang.Thread.run(Thread.java:864)
,W/ContextImpl( 4467): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GCM     ( 1367): GCM config loaded
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4467, uid=10154, userID:0
,I/MusicLeanback( 4467): Conditions not met for autocaching.
,I/MusicLeanback( 4467): Stop autocaching.
D/PMS     (  903): releaseWL(43aabab8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  903): releaseWL(424e7a90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8833 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/104.81.130.175
,W/ActivityManager(  903): Sleep timeout!  Sleeping now.
,D/PMS     (  903): releaseWL(42629700): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/GAV2    ( 4555): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4414): Test app app.js loaded
I/jxcore-log( 4414): 
,I/Choreographer( 4414): Skipped 525 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b291b8 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4414): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    ( 4672): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  903): killProcessQuiet, pid=4296
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4296:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4296
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3866
,I/ActivityManager(  903): Killing 3866:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3866
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1401): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1401): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1401): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  903): acquireWL(44016150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42174cb0: PendingIntentRecord{4204ab18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120345, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(44016150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(426eb870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/PMS     (  903): acquireWL(43461ae0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,V/AlarmManager(  903): sending alarm PendingIntent{41db2d48: PendingIntentRecord{424be290 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=126898, Int=0
D/PMS     (  903): releaseWL(426eb870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(44102030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43461ae0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(44102030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(44108d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(44108d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1401): service - has update message, not stop
,D/AutoSetting( 1401): service - mHandler: update timezone
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1495): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1495): service - onCreate()
D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1495): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1495): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1495): service - mHandler: update timezone
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1495): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1495): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1495): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41efc608 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  903): acquireWL(44061a60): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(44061a60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43c87628): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(43c87628): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42d94618): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(42d94618): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43b6dee8): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(43b6dee8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(4261db68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{41ffc368: PendingIntentRecord{424d7270 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135968, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{4239d8c8: PendingIntentRecord{424ffce8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141788, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1367/10028)
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(43b78788): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(4261db68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  903): acquireWL(440cd8d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  903): releaseWL(440cd8d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6dfc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(43b78788): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{438a2240 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(43ac3780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41db2d48: PendingIntentRecord{424be290 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=156925, Int=0
,D/PMS     (  903): acquireWL(43fca298): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(43ac3780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(425b44a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=14 [57][8][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42d6d970): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
,D/PMS     (  903): releaseWL(43fca298): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(425b44a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4405c2a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/NewsWeather( 4672): Last usage 0, idle 1452773916s, sync interval 2592000s
,I/NewsWeather( 4672): setPeriodicSync in seconds 2592000
D/PMS     (  903): releaseWL(4405c2a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4672): Skip sync for lookup editions
,I/NewsWeather( 4672): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4672): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4672): Unrecoverable authentication exception
E/NewsWeather( 4672): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41efe700 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 2 10 3 12
,D/PMS     (  903): acquireWL(43890bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,E/NewsWeather( 4672): Failed to syncNewsAppData
,E/NewsWeather( 4672): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  903): releaseWL(43890bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43019af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 109176, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  903): releaseWL(42d6d970): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
,D/PMS     (  903): releaseWL(43019af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43303950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43303950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  903): acquireWL(432d9d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(432d9d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - onDestroy() END
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/AutoSetting( 1495): service - handleMessage() stop self
,D/AutoSetting( 1495): service - onDestroy() END
,D/AutoSetting( 1495): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4312
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  903): Killing 4312:com.htc.backup/1000 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4312
,D/PMS     (  903): acquireWL(437ba1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{42729d38: PendingIntentRecord{42540e18 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=168895, Int=0
,D/PMS     (  903): releaseWL(437ba1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1234): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(42585968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42174cb0: PendingIntentRecord{4204ab18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180345, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42585968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(435d85a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41db2d48: PendingIntentRecord{424be290 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=186991, Int=0
,D/PMS     (  903): acquireWL(4381a910): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(435d85a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(435440c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(4381a910): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(435440c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(42e6a458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): releaseWL(42e6a458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43363c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bdc5a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,V/AlarmManager(  903): sending alarm PendingIntent{41db2d48: PendingIntentRecord{424be290 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=221630, Int=0
,D/PMS     (  903): releaseWL(43363c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42be2640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=19 [21][4][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(432f8538): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(43bdc5a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  903): releaseWL(42be2640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43382df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43382df0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4672): Last usage 0, idle 1452773981s, sync interval 2592000s
I/NewsWeather( 4672): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4672): Skip sync for lookup editions
,I/NewsWeather( 4672): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4672): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4672): Unrecoverable authentication exception
E/NewsWeather( 4672): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4672): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4672): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41b65ca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 2 9 3 12
,D/PMS     (  903): acquireWL(4328b488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  903): releaseWL(4328b488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4672): Failed to syncNewsAppData
,E/NewsWeather( 4672): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e35a08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 157424, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  903): releaseWL(432f8538): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1417/10028)
D/PMS     (  903): releaseWL(42e35a08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43b77618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(43b77618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  903): acquireWL(443ce5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(443ce5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43af36f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42174cb0: PendingIntentRecord{4204ab18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240345, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43af36f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(438522e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41db2d48: PendingIntentRecord{424be290 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=251696, Int=0
,D/PMS     (  903): acquireWL(43770f28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/PMS     (  903): releaseWL(438522e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4363a4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43770f28): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(4363a4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(434e3488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434e3488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(434be4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(434be4d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42749e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42174cb0: PendingIntentRecord{4204ab18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300345, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42749e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42713108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(42713108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4414): --= Surplus to requirements =--
I/jxcore-log( 4414): 
I/jxcore-log( 4414): ****TEST TOOK:  ms ****
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4414): 
,E/cutils-trace( 4754): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4754): ====startRecUseTime====
D/htc.customization.log.level( 4754):  is 
,W/CustomizationLogLevel( 4754): Level value is invalid, use default level 2
,D/CustomizationManager( 4754):  Read ACC file spent 0.109 (s)
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4754): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4754): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4754): Parsing tag category name = system
,I/CustomizationCIDLoader( 4754): Parsing tag category name = application
I/CustomizationCIDLoader( 4754): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4754): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4754): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4754): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4754): Parsing tag category name = Settings
D/CustomizationManager( 4754):  Read CID file spent 0.160 (s)
,D/CustomizationManager( 4754):  All configurations done spent 0.160 (s),
,W/HtcNativeFlag( 4754): Fail to get flag string for type 'customer', use default value,
W/HtcNativeFlag( 4754): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4754): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4754): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4754, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=4414
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903): Killing 4414:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  903):   Force finishing activity ActivityRecord{42e42dd8 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1202): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4414 uid 10189
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  903): WIN DEATH: Window{42e4f440 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  903): Client connection lost with reason: 4
,I/dalvikvm-heap( 4026): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
,D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/acms    ( 1864): Unregistering com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,E/acms    ( 1864): Could not unregister removed application com.test.thalitest
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/VoicemailCleanupService( 1279): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,I/Launcher( 1266): Deferring update until onResume
,D/Launcher( 1266): waitUntilResume // bindAppsRemoved
,W/GeofencerStateMachine( 1417): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
D/PMS     (  903): acquireWL(42549378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,D/PMS     (  903): releaseWL(42549378): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PackageBroadcastService( 1217): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4769 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1234 :
,D/PhoneApp( 1234): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4769): install
,I/MultiDex( 4769): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  903): Delaying start of: ServiceRecord{43b1ca60 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4769): loading existing secondary dex files
,I/MultiDex( 4769): load found 1 secondary dex files
,I/MultiDex( 4769): install done
,I/PeopleContactsSync( 1217): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1217, uid=10028, userID:0
,I/Icing   ( 1217): doRemovePackageData com.test.thalitest
D/PMS     (  903): acquireWL(435c2d18): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4787 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  903): releaseWL(435c2d18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4769): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4787): install
,I/MultiDex( 4787): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4787): loading existing secondary dex files
,I/MultiDex( 4787): load found 1 secondary dex files
,I/MultiDex( 4787): install done
I/ActivityManager(  903): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1401): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ProviderInstaller( 4787): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/[PluginManager]RegisterService( 1401): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=4283
,I/ActivityManager(  903): Killing 4283:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1266): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2921): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4283
,I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4807 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4769): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
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
E/SQLiteDatabase( 4769): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4769): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4769): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4769): threadid=12: thread exiting with uncaught exception (group=0x416ebe30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4769): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4769): Process: com.google.android.gms.drive, PID: 4769
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
E/AndroidRuntime( 4769): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4769): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4769): 	at ctn.run(SourceFile:985)
E/SQLiteLog( 2921): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2921): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644040b0
W/dalvikvm( 2921): threadid=16: thread exiting with uncaught exception (group=0x416ebe30)
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 4769): killProcess, pid=4769
D/Process ( 4769): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 2921): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2921): Process: com.google.android.googlequicksearchbox:search, PID: 2921
E/AndroidRuntime( 2921): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2921): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2921): 	at cid.d(PG:186)
E/AndroidRuntime( 2921): 	at clo.g(PG:594)
E/AndroidRuntime( 2921): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2921): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2921): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2921): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2921): 	at clr.tL(PG:827)
E/AndroidRuntime( 2921): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2921): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2921): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2921): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2921): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2921): killProcess, pid=2921
D/Process ( 2921): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,I/ActivityManager(  903): Recipient 4769
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4769) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2921
,D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2921): Died!
,D/WifiService(  903): Client connection lost with reason: 4
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2921) has died.
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,W/PackageManager(  903): Unable to load service info ResolveInfo{42663dd0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4807): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4807): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4807): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4807): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4807): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4807): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4807): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4807): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4807): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4807): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4807): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4807): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4807): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4807): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4807): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4807): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4807): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4807): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4807): Couldn't open ClientFlag.db for writing (will try read-only):
,E/SQLiteOpenHelper( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4807): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4807): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4807): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4807): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4807): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4807): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4807): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4807): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4807): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4807): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4807): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4807): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4807): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4807): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4807): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4807): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4807): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4807): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4807): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4807): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4807): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4807): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4807): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4807): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4807): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4807): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4807): threadid=11: thread exiting with uncaught exception (group=0x416ebe30)
,E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4807): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4807): Process: com.google.android.apps.docs, PID: 4807
E/AndroidRuntime( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4807): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4807): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4807): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4807): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4807): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4807): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,E/SQLiteDatabase( 4807): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4807): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4807): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4807): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4807): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4807): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4807): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4807): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4807): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4807): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4807): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4807): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4807): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4807): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4807): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4807): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4807): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4807): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4807): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4807): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4807): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4807): Opened ClientFlag.db in read-only mode
D/Process ( 4807): killProcess, pid=4807
,D/Process ( 4807): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4825 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Recipient 4807
,I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4807) has died.
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4838 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4825): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4825): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4825): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4825): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4825): threadid=10: thread exiting with uncaught exception (group=0x416ebe30),
,E/AndroidRuntime( 4825): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4825): Process: com.android.keychain, PID: 4825
E/AndroidRuntime( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4825): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4825): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4825): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  903): App crashed! Process: com.android.keychain
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41baeed8 +
,I/Prism.WidgetManager( 1266): onLoadItems() +
,D/AppTag  ( 4838): getInstance(Context context)
,D/AppTag  ( 4838): getInstance(Context context)
,D/AppTag  ( 4838): onCreate()
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(432e66c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4026 10160 null
,D/Process ( 4825): killProcess, pid=4825
,D/Process ( 4825): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/dalvikvm-heap( 4026): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452774081499.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/ActivityManager(  903): Recipient 4825
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.keychain (pid 4825) has died.
D/PMS     (  903): releaseWL(432e66c0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10255ms
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4855 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  903): Killing 4336:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4336
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4336
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4855): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4855 dbg=false s=true
,I/DeviceManagement( 4855): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4855): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4855): WorkflowService: Starting workflow service
I/DeviceManagement( 4855): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b4e0f8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4855): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4855): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4855): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4855): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  903): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4870 uid=10099 gids={50099, 3003, 5012}

```
