#### Test 57617811ecc172f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [12][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
E/cutils-trace( 4532): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4532): ====startRecUseTime====
D/htc.customization.log.level( 4532):  is 
W/CustomizationLogLevel( 4532): Level value is invalid, use default level 2
D/CustomizationManager( 4532):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4532): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4532): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4532): Parsing tag category name = system
I/CustomizationCIDLoader( 4532): Parsing tag category name = application
I/CustomizationCIDLoader( 4532): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4532): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4532): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4532): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4532): Parsing tag category name = Settings
D/CustomizationManager( 4532):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4532):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4532): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4532): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4532): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4532): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4532
D/PMS     (  911): acquireHCC(43930dc8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
D/PMS     (  911): acquireHCC(43a3d2c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
W/asset   (  911): Copying FileAsset 0x6abba958 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1138874432
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c15280
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/PMS     (  911): acquireWL(4262e148): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/ActivityManager(  911): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4543 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4543): Copying FileAsset 0x5c7df428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4543): Binding Chromium to main looper Looper (main, tid 1) {41a9f568}
I/LibraryLoader( 4543): Expected native library version number "",actual native library version number ""
I/chromium( 4543): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4543): Initializing chromium process, renderers=0
D/PMS     (  911): acquireWL(4361da18): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  911): acquireWL(43798bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): java.lang.Throwable: stack dump
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422e0ce8:true
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  911): releaseWL(43798bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4543): 1101746080: getState(). Returning 12
I/Adreno-EGL( 4543): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4543): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4543): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4543): Local Branch: 
I/Adreno-EGL( 4543): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4543): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4543):                  aa63bbd948f41d15fc72f585e
W/chromium( 4543): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/AutoSetting( 1327): service - mHandler: update timezone
D/AutoSetting( 1327): service - handleMessage() stop self
W/dalvikvm( 4543): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4543): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/AutoSetting( 1327): service - handleMessage() quit looper
D/AutoSetting( 1327): service - onDestroy() END
W/dalvikvm( 4543): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4543): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4543): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/Process (  911): killProcessQuiet, pid=4294
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/dalvikvm( 4543): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4543): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4543): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4543): CordovaWebView is running on device made by: HTC
I/ActivityManager(  911): Killing 4294:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  911): Recipient 4294
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1491): service - onCreate()
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1491): service - mHandler: update timezone
,D/AutoSetting( 1491): service - processTimeZoneID() system nitz: 
D/AutoSetting( 1491): service - processTimeZoneID() system nitz is valid: false (false)
D/AutoSetting( 1491): service - processTimeZoneID() single-timezone, pop up dialog
D/AutoSetting( 1491): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41eca2d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1119): com.htc.htclocationservice 1 8 3 11
W/AwContents( 4543): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1274
W/ResourceType( 4543): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  911): Enable input method client, pid=4543
I/InputMethodManager( 4543): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae6650, mServedView=org.apache.cordova.engine.SystemWebView{41aac2b8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4543): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  911): Displayed com.test.thalitest/.MainActivity: +303ms
D/PMS     (  911): releaseWL(4262e148): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4543): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4543): JniHelper::setJavaVM(0x41575048), pthread_self() = 1556165896
I/chromium( 4543): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/HtcModeClient( 1491): handler message = 4011
E/HtcModeClient( 1491): Check connection and retry 11 times.
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 11.230MB for 323830-byte allocation
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 11.496MB for 485740-byte allocation
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 11.875MB for 728606-byte allocation
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 12.464MB for 1092904-byte allocation
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 13.340MB for 1639352-byte allocation
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 14.716MB for 2459024-byte allocation
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4543): Grow heap (frag case) to 15.407MB for 2287544-byte allocation
,W/jxcore-log( 4543): Initializing JXcore engine
,W/jxcore-log( 4543): JXcore engine is ready
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
D/PMS     (  911): releaseHCC(43930dc8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  911): releaseHCC(43a3d2c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4543): Starting JXcore engine
,W/jxcore-log( 4543): Platform android
W/jxcore-log( 4543): 
,W/jxcore-log( 4543): Process ARCH arm
W/jxcore-log( 4543): 
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/jxcore-log( 4543): JXcore Cordova bridge is ready!
I/jxcore-log( 4543): 
,W/jxcore-log( 4543): JXcore engine is started
,I/jxcore-log( 4543): Toggling radios to true
I/jxcore-log( 4543): 
,D/BluetoothAdapter( 4543): enable(): BT is already enabled..!
,D/WifiManager( 4543): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  911): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  911): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  911): Settings:Agentvalue: 2
W/Settings:Agent(  911): >> traceCallingStack()
W/Settings:Agent(  911): Process.myPid(): 911
,W/Settings:Agent(  911): Process.myTid(): 1347
W/Settings:Agent(  911): Process.myUid(): 1000
W/Settings:Agent(  911): 
W/Settings:Agent(  911): 
,W/System.err(  911): java.lang.Throwable: stack dump
D/WifiService(  911): New client listening to asynchronous messages
D/WifiService(  911): setWifiEnabled: true pid=4543, uid=10389
E/WifiService(  911): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  911): isSprintWifiRestricted(): false
I/WifiService(  911): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  911): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  911): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  911): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  911): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  911): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  911): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  911): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  911): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  911): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  911): 
W/Settings:Agent(  911): << traceCallingStack(): 4(ms)
D/WifiManager( 4543): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  911): doBoolean: DISCONNECT
D/WifiManager( 4543): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): TDLS: Tear down peers
I/wpa_supplicant( 1180): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4543): Radios toggled
I/jxcore-log( 4543): 
I/jxcore-log( 4543): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4543): 
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1180): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1180): TDLS: Remove peers on disassociation
D/HTCRequest(  911): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/HTCRequest(  911): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8427bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1180): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_w,ext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  911):    returned true
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/WifiPerfLock(  911): release()
D/WifiStateMachine(  911): PerfLock released for exiting ConnectedState
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/HTCRequest(  911): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  911): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  911): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED,
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
,D/Tethering(  911): interfaceStatusChanged wlan0, false
D/ConnectivityService(  911): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  911): acquireWL(4260cd58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 911 1000 null
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  911): [RunningState] Stop DHCP
D/WifiNative-wlan0(  911): doBoolean: RECONNECT
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): Fast associate: Old scan results
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20582 mDataStallAlarmIntent=PendingIntent{432dcb78: PendingIntentRecord{422aab50 android broadcastIntent}}
D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): Enter handleNetworkDisconnect
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  911):    returned true
,D/UsbnetStateTracker(  911): isAvailable+-
D/UsbnetStateTracker(  911): reconnect
,D/UsbnetStateTracker(  911): isAvailable+-
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  911): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  911): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  911): default: reconnect()
D/MDST    (  911): default: setTeardownRequested(false)
,D/MDST    (  911): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3883): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  911): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3883): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  911): New client listening to asynchronous messages
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS,
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  911): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  911): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  911): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 2873): Read error: ssl=0x63f8ad28: I/O error during system call, Connection timed out
,D/WISPrService( 3883): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
V/NativeCrypto( 2873): SSL shutdown failed: ssl=0x63f8ad28: I/O error during system call, Broken pipe
D/WISPrService( 3883): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  911): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/ConnectivityService(  911): resetConnections(wlan0, 3)
D/PMS     (  911): acquireWL(428475a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  362): [NET] entry_id:3   entry:0xb795a590  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb795ee40  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb795ed90  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb795ef70  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb7955c20  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb795a458  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb795a2a8  removed 
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  911): flush DNS cache for net 1(wlan0)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): acquireWL(43385db0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  911): startScan Pid: 911 Uid 1000
D/WifiNative-wlan0(  911): doBoolean: SCAN
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  911):    returned false
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  911): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (2873/10029)
D/BatSI   (  911): WIFI scan started for: 650a0301 uid:1000
I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): releaseWL(428475a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): releaseWL(43385db0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
,D/ConnectivityService(  911): mActiveDefaultNetwork: -1
,D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
,D/PMS     (  911): releaseWL(4361da18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  911): bSetPropertyMultiRAB:false
D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  911): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  911): ipv4Default null
I/Tethering(  911): No IPv4 upstream interface, giving up.
,D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/CaptivePortalTracker(  911): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3966): type=WIFI subType= reason=null isConnected=false
,D/CaptivePortalTracker(  911): NoActiveNetworkState
I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/PMS     (  911): acquireWL(42dc9850): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3966/10154)
D/PMS     (  911): releaseWL(42dc9850): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2379/10021)
,I/ActivityManager(  911): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4602 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4602): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4602): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4602): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/SystemClassLoaderAdder( 4602): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 4602): Preparing secondary program dexes.
V/DexLibLoader( 4602): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4602): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4602): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4602): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4602): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4602): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4602): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4602): Dex already copied
D/OdexVerifier( 4602): Odex verification is skipped.
V/DexLibLoader( 4602): Creating class loader
V/DexLibLoader( 4602): Finished creating class loader
V/DexLibLoader( 4602): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4602): Dex already copied
D/OdexVerifier( 4602): Odex verification is skipped.
,V/DexLibLoader( 4602): Creating class loader
,V/DexLibLoader( 4602): Finished creating class loader
V/DexLibLoader( 4602): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4602): Dex already copied
D/OdexVerifier( 4602): Odex verification is skipped.
,V/DexLibLoader( 4602): Creating class loader
V/DexLibLoader( 4602): Finished creating class loader
V/DexLibLoader( 4602): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4602): Dex already copied
D/OdexVerifier( 4602): Odex verification is skipped.
V/DexLibLoader( 4602): Creating class loader
V/DexLibLoader( 4602): Finished creating class loader
,V/DexLibLoader( 4602): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4602): DexLibLoader.ensureDexLoaded took 23 ms,
,W/dalvikvm( 4602): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-75
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1180): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1180): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1180): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1180): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  911): doString: LIST_DONGLES
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 3
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 1
I/wpa_supplicant( 1180): wpa_s->is_screen_on 1
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): selected network = 1
D/wpa_supplicant( 1180): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84294e8  current_ssid=0x0
D/wpa_supplicant( 1180): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1180): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1180): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1180): check if in concurrent case
,I/wpa_supplicant( 1180): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1180): RSN: PMKSA cache search - network_ctx=0xb84294e8 try_opportunistic=0
D/wpa_supplicant( 1180): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1180): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1180): nl80211: Set mode ifindex 22 iftype 2 (STATION),
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1180): nl80211: Unsubscribe mgmt frames handle 0xb8428718 (mode change)
D/wpa_supplicant( 1180): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8428718
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb8428718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1180):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180):   * freq=2412
D/wpa_supplicant( 1180):   * Auth Type 0
D/wpa_supplicant( 1180):   * WPA Versions 0x2
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1180): nl80211: Connect request send successfully
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  911): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (779) for get BSS: id=0,
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-50
I/wpa_supplicant( 1180): tsf=0000000089581264
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-51
I/wpa_supplicant( 1180): tsf=0000000089581282
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-52
I/wpa_supplicant( 1180): tsf=0000000089581277
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2452
I/wpa_supplicant( 1180): level=-75
I/wpa_supplicant( 1180): tsf=0000000089581286
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=4
I/wpa_supplicant( 1180): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000000089581290
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC5999698
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-87
I/wpa_supplicant( 1180): tsf=0000000089581293
I/wpa_supplicant( 1180): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=UPC Wi-Free,
I/wpa_supplicant( 1180): ####
D/WifiStateMachine(  911): == begin of scan result ==
D/WifiStateMachine(  911): == (6) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  911): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 89581264, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  911): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 89581282, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 89581277, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2452, timestamp: 89581286, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 89581290, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 89581293, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  911): add 6 to mScanResults
D/BatSI   (  911): WIFI scan stopped for: 640a0301 uid:1000
D/WifiNotificationController(  911): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  911): getDiscoveryDongleList
D/WifiStateMachine(  911): == begin of scan result ==
D/WirelessDisplayService(  911): getDiscoveryDongleList
,D/WifiStateMachine(  911): == (6) end of scan result ==
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,W/dalvikvm( 4602): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4602): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/Tethering(  911): interfaceLinkStateChanged wlan0, false
D/Tethering(  911): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Connect event
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1180): State: ASSOCIATING -> ASSOCIATED
,D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Add randomness: count=11 entropy=6
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on association
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  911): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1180): EAPOL: enable timer tick
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1180): getPrivFuncNum +,	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1180): Get randomness: len=32 entropy=7
D/WifiMonitor(  911): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  911): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  911): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  911): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  911): handleAssociatedWithEvent. bLFR =false
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  911): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  911): interfaceStatusChanged wlan0, true
,D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  911): Enter handleAssociatedWithEvent
D/WifiStateMachine(  911): Associated
D/Tethering(  911): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  911): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  911): Exit handleAssociatedWithEvent
D/WifiStateMachine(  911): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  911): updateConnectedAP...
D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  911): updateConnectedAP...
,E/FbInjectorInitializer( 4602): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84289f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed3b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    broadcast key
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1180): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1180): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1180): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1180): set send_ind_to_ndc = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1180): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1180): EAPOL authentication completed successfully
I/wpa_supplicant( 1180): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  911): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  911): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  911): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  911): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  911): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  911): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  911): This record is existed, only update it...
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  911): updateConnectedAP...
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Tethering(  911): interfaceLinkStateChanged wlan0, true
,D/Tethering(  911): interfaceStatusChanged wlan0, true
,D/Tethering(  911): [isWifi] getHotspotEnabled: false
,D/WISPrService( 3883): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3883): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): mActiveDefaultNetwork: -1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  911): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  911): updateConnectedAP...
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
D/WifiStateMachine(  911): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/DhcpStateMachine(  911): [StoppedState] Start DHCP
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 1
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
,D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  911):    returned null,
E/WifiStateMachine(  911): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  911): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  911):    returned null
D/WifiStateMachine(  911): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  911): acquireWL(432cf828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 911 1000 null
D/WifiStateMachine(  911): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  911): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42369ef8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42369ef8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4602): Verify
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4602): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4602): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  911): killProcessQuiet, pid=4324
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4324:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4324
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1327): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  911): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4629 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1327): Util - no network available!
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
D/AutoSetting( 1327): service - onCreate()
D/AutoSetting( 1327): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1327): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  911): request 424ce5f8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1327): service - mHandler: cancel location update
D/AutoSetting( 1327): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4602): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4629): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4629): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4629): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4629): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4602): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4602): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  911): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4645 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4629/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4629/10079)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4629/10079)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4602): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/Process (  911): killProcessQuiet, pid=4341
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4662 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  911): Killing 4341:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4341
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 9.960MB for 84664-byte allocation
,E/dalvikvm( 4602): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4602): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4662): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 9.975MB for 28144-byte allocation
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4602): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4602): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4602): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4602): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4602): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4602): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4602): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4602): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4602): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4662): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4602): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4602): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4602): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4602): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4602): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4602): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4602): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/HtcModeClient( 1491): handler message = 4011
,E/HtcModeClient( 1491): Check connection and retry 12 times.
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 10.018MB for 39954-byte allocation
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 10.094MB for 79892-byte allocation
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
,V/WebViewChromiumFactoryProvider( 4662): Binding Chromium to main looper Looper (main, tid 1) {41aa33c0}
,I/LibraryLoader( 4662): Expected native library version number "",actual native library version number ""
,I/chromium( 4662): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4662): Initializing chromium process, renderers=0
,D/PMS     (  911): acquireWL(4366fd58): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/PMS     (  911): acquireWL(43650d10): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4662): BLUETOOTH permission is missing!
D/PMS     (  911): releaseWL(4366fd58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4662): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4662): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4662): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4662): Local Branch: 
I/Adreno-EGL( 4662): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4662): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4662):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4662): Starting up...
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
,D/Process (  911): killProcessQuiet, pid=4311
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4602): Grow heap (frag case) to 10.281MB for 75760-byte allocation
I/ActivityManager(  911): Killing 4311:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/iu.Environment( 2182): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2182): num queued entries: 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
I/ActivityManager(  911): Recipient 4311
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/iu.UploadsManager( 2182): num updated entries: 0
I/iu.SyncManager( 2182): NEXT; no task
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
D/wpa_supplicant( 1180): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1180): EAPOL: disable timer tick
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getAllNetworkInfo called by com.test.thalitest (4543/10389)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42607f60 u0 ReceiverList{42608990 4602 com.facebook.katana/10027/u0 remote:41bca230}}
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42607f60 u0 ReceiverList{42608990 4602 com.facebook.katana/10027/u0 remote:41bca230}}
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425fcef8 u0 ReceiverList{425fd4c0 4602 com.facebook.katana/10027/u0 remote:426011e8}}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): acquireWL(42e756f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42e756f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  911): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  911): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4602): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4602): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(432cf828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  911): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  911): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WifiStateMachine(  911): gateway: /192.168.1.1
,D/WifiNative-wlan0(  911): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  911): VerifyingLinkState enter
D/WifiStateMachine(  911): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  911): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  911): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  911): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  911): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  911): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20584 delay=15s
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  911): WAN detection
V/NetworkPolicy(  911): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  911): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WISPrService( 3883): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  911): Provision feature enable=false
D/ConnectivityService(  911): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  911): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  911): default: teardown()
D/MDST    (  911): default: setTeardownRequested(true)
D/MDST    (  911): default: setEnableApn apnType =default , enable=false
D/MDST    (  911): default: setTeardownRequested(true)
D/ConnectivityService(  911): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  911): syncGetConfiguredNetworks
E/ConnectivityService(  911): Unexpected mtu value: android.net.wifi.WifiStateTracker@42424ed8
D/ConnectivityService(  911): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
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
D/ConnectivityService(  911): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  911): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  911): handleConnectivityChange: resetting
D/Nat464Xlat(  911): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  911): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WirelessDisplayService(  911): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  911):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  911): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  911): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  911): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  911): acquireWL(426070e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4629/10079)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  911): acquireWL(424cddc0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2182): Checkin interval check for package: unspecified last checkin: 1454063330477 min interval config: 0 actual interval: 30934
D/PMS     (  911): acquireWL(42b8f480): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(424cddc0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2182): Checking schedule, now: 1454063361417 next: 1454063360421
,I/CheckinService( 2182): active receiver: enabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2182): Preparing to send checkin request
I/EventLogService( 2182): Accumulating logs since 1454063325569
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  911): mActiveDefaultNetwork: WIFI
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/CheckinRequestBuilder( 2182): Checkin reason type: 8 attempt count: 1
D/PMS     (  911): releaseWL(426070e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2182): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  911): acquireWL(434b8348): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(434b8348): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42620770): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42620770): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43396390): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2182/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=100 [1][1][0]
,V/GLSActivity( 2873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  911): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4736 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  911): releaseWL(43396390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4736): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4736): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4736): install
,I/MultiDex( 4736): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4736): loading existing secondary dex files
,I/MultiDex( 4736): load found 3 secondary dex files
,I/MultiDex( 4736): install done
,W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4736): VFY: unable to resolve instance field 36
,W/dalvikvm( 4736): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4736): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4736): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 2182): Restart initialization of location
,E/MDM     ( 1224): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/ActivityManager(  911): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 2873): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/dalvikvm( 4736): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/AuthorizationBluetoothService( 2873): Proximity feature is not enabled.
E/dalvikvm( 4736): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4736): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4736): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4736): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 2873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  911): acquireWL(42616ff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42616ff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4736): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  369): PrepareKeyRequest: nonce=2537824223
,I/WVCdm   (  369): CdmEngine::CloseSession
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4736): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4736): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4736):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (4736/10029)
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  911): releaseWL(4260cd58): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  911): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  911): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/Settings( 4736): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/Tethering(  911): bSetPropertyMultiRAB:false
,D/Tethering(  911): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  911): NoActiveNetworkState
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.setupwizard (4629/10079)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.google.android.music (3966/10154)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,I/NetworkMonitor( 3966): type=WIFI subType= reason=null isConnected=true
,I/Tethering(  911): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  911): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  911): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  911): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
I/Tethering(  911): Found interface wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1180): nl80211: survey data missing!
D/AccTypeManager( 1368): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/Tethering(  911): TetherMasterSM: InitialState processMessage what=3
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (4001/10053)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.backuptransport (1560/10029)
D/PMS     (  911): acquireWL(424ed738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  911): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/PMS     (  911): acquireWL(4363abd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/GpsLocationProvider(  911): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  911): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  911): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  911): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/PMS     (  911): releaseWL(4363abd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  911): releaseWL(424ed738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2379/10021)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1368): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1368): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AutoSetting( 1327): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4629): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4629): onReceive CONNECTIVITY_CHANGE networkType=1
,E/ExternalAccountType( 1368): Unsupported attribute readOnly
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
,D/AutoSetting( 1327): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1327): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1327): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1327): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1327): service - handleMessage() setting current location null
D/AutoSetting( 1327): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1327): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.magazines (4662/10151)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1327/10055)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
,I/CheckinService( 2182): Checkin interval check for package: unspecified last checkin: 1454063330477 min interval config: 0 actual interval: 32026
D/PMS     (  911): acquireWL(43a01808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43a01808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2182): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2182): num queued entries: 0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,I/iu.UploadsManager( 2182): num updated entries: 0
,I/iu.SyncManager( 2182): NEXT; no task
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/libc    ( 2873): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 2873): [NET] getaddrinfo-,err=8
D/libc    ( 2873): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 2873): [NET] getaddrinfo-, 1
,D/libc    ( 2873): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/ConnectivityService(  911): getAllNetworkInfo called by com.test.thalitest (4543/10389)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): acquireWL(43382468): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/libc    (  362): [NET] +++++ res_nsend xid =968 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=1911715170
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 248
D/libc    (  362): [NET]res_nsend:resplen=79
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2873): [NET] getaddrinfo_proxy-, success
,I/WVCdm   (  369): CdmEngine::CloseSession
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4736): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4736): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4736):                  aa63bbd948f41d15fc72f585e
D/libc    ( 2873): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2873): [NET] getaddrinfo-,err=8
,I/Adreno-EGL( 4736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4736): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4736): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4736): Local Branch: 
I/Adreno-EGL( 4736): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4736): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4736):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2182): Classify the device as Phone.
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2182): [NET] getaddrinfo-,err=8
D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2182): [NET] getaddrinfo-, 1
,D/libc    ( 2182): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =5164 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 160
D/libc    (  362): [NET]res_nsend:resplen=84
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2182): [NET] getaddrinfo_proxy-, success
D/libc    ( 2873): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2873): [NET] getaddrinfo-,err=8
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
,D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
D/libc    ( 2182): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2182): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2182): Sending checkin request (12260 bytes)
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4543): 
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=5 [19][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  911): BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,W/fb4a(:<default>):UserScope( 4602): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4602): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/PMS     (  911): acquireWL(436bc508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): releaseWL(43382468): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (2873/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: starting a change hold
D/PMS     (  911): releaseWL(436bc508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(4385f220): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (2873/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/ConnectivityService(  911): reportInetCondition for net 1, percentage: 100 by  (2873/10029)
D/ConnectivityService(  911): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  911): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/PMS     (  911): releaseWL(4385f220): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4602): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,I/CheckinRequestBuilder( 2182): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
I/ActivityManager(  911): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2182): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,D/ConnectivityService(  911): getNetworkInfo networkType=9 called by com.google.android.gms (2182/10029)
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
,I/CheckinRequestBuilder( 2182): Classify the device as Phone.
,I/CheckinTask( 2182): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2182): Checking schedule, now: 1454063363855 next: 1454586300852
,I/CheckinService( 2182): active receiver: disabled
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,I/CheckinService( 2182): Checking schedule, now: 1454063363872 next: 1454586300852
,I/CheckinService( 2182): active receiver: disabled
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
,I/SensorManager(  911): mEventCount = 750
,D/CheckinService( 2182): Recording last checkin time for package unspecified as 1454063363876
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(42b8f480): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/GCM     ( 2873): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  911): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  911): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  911): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4543): 
,D/PMS     (  911): releaseWL(43650d10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4543): 
,D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =fd6a +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  911): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  911): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  911): acquireWL(43427368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10074}
,V/AlarmManager(  911): sending alarm PendingIntent{4235e098: PendingIntentRecord{439347c8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454063364904, Int=0
,D/PMS     (  911): releaseWL(43427368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4175): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4175): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/GAV2    ( 4662): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1491): handler message = 4011
,E/HtcModeClient( 1491): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1491): Don't start project servcice
,D/HtcModeClient( 1491): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1491): connectState: CONNECTION_READY = false
D/SilentMusic( 1491): call stop
D/HtcModeClient( 1491): close connection
,W/HtcModeClient( 1491): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1491): read the terminate packet, so break
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiStateMachine(  911): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  911): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  911): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4784 uid=10078 gids={50078}
,D/PMS     (  911): acquireWL(432dd9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10078}
V/AlarmManager(  911): sending alarm PendingIntent{424025c0: PendingIntentRecord{42492170 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454063366978, Int=60000
,D/PMS     (  911): releaseWL(432dd9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4784): SMSBackupAgentService started
,D/SMSBackup( 4784): Checking restore status
,D/SMSBackup( 4784): Restore complete
,D/SMSBackup( 4784): cancelCheckAlarm
,D/SMSBackup( 4784): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/Process (  911): killProcessQuiet, pid=4364
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4364:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4364
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=3495
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3495:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3495
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=16 [6][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  911):    returned true
D/WifiStateMachine(  911): [ScoreAP] + current TXpacket:45, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
D/WifiStateMachine(  911): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,I/jxcore-log( 4543): Test app app.js loaded
I/jxcore-log( 4543): 
,W/dalvikvm( 4543): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4543): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4543): BLE advertisement is supported
I/jxcore-log( 4543): 
,I/chromium( 4543): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42db6c08 u0 com.htc.htclocationservice/.AutoSettingService}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.facebook.katana (4602/10027)
,V/LightsService(  911): setLight #0: color=#3f
,V/LightsService(  911): setLight #0: color=#3c
,V/LightsService(  911): setLight #0: color=#35
,V/LightsService(  911): setLight #0: color=#2e
,V/LightsService(  911): setLight #0: color=#28
,V/LightsService(  911): setLight #0: color=#21
,V/LightsService(  911): setLight #0: color=#1a
,V/LightsService(  911): setLight #0: color=#14
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1368): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): acquireWL(43a5ac80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4222 10111 null
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Launcher( 1274): Deferring update until onResume,
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
W/AccTypeManager( 1368): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1368): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
D/PMS     (  911): releaseWL(43a5ac80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/[PluginManager]RegisterService( 1327): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1327): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
,E/ExternalAccountType( 1368): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(423448d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4150 10160 null
,D/PMS     (  911): acquireWL(425aafd8): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 13.529MB for 1821008-byte allocation
D/PMS     (  911): releaseWL(423448d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
,D/PMS     (  911): releaseWL(425aafd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  911): acquireWL(423f93f8): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(423f93f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  911): acquireWL(41ef4560): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  911): Unable to load service info ResolveInfo{42446558 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  911): releaseWL(41ef4560): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(422f7470): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2182): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2182): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2182): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2844): UpdateCorporaTask done [took 477 ms] updated apps [took 477 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  911): applying state to connected service
,D/LocationProviderProxy(  911): applying state to connected service
D/PMS     (  911): acquireWL(42d88020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42d88020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(434b91f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43779590): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(434b91f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43779590): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=25 [4][1][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  911): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  911): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b30d10 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2182): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2182): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  911): releaseWL(422f7470): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b30d10 -
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,D/PhoneApp( 1245): -- N3 =0
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
,I/SensorManager(  911): mEventCount = 900
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{4330ed08 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WifiDataStallTracker(  911): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  911): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  911): updateDataStallInfo: mDataStallTxRxSum={txSum=159 rxSum=143} preTxRxSum={txSum=131 rxSum=114}
D/WifiDataStallTracker(  911): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  911): onDataStallAlarm: tag=20584 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20585 delay=15s
D/PMS     (  911): acquireWL(43afc928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
V/AlarmManager(  911): sending alarm PendingIntent{424cd8e0: PendingIntentRecord{4245c1d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105898, Int=0
D/PMS     (  911): releaseWL(43afc928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42156e08
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42156e08, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073af8
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@436c3218
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,W/PMS     (  911): mWirelessDisplayManager is null
D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE,
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 316ms
,D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
,D/PMS     (  911): OOBE c monitor 11
,I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42d2e2a0)
I/InputMethodManagerService(  911): Disable input method client, pid=4543
,D/PMN     (  911): wakingUp
W/ResourceType( 4543): No package identifier when getting name for resource number 0x00000064
D/NfcService( 1260): ScreenObserver: OFF
I/InputMethodManager( 4543): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aac2b8 VFEDH.C. .F...... 0,0-720,1134 #64}
V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1260): applyRouting - 0
I/WindowManager(  911): No lock screen! windowToken=null
D/PMS     (  911): acquireWL(436ac988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMN     (  911): onScreenOn
,D/NfcService( 1260): applyRouting -2
D/PMS     (  911): releaseWL(436ac988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  911): acquireWL(438edad0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  911): releaseWL(438edad0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=98
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2379): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2379): [MTP][onReceive]-
,D/NfcService( 1260): applyRouting - 0
D/AutoSetting( 1327): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1260): applyRouting -2
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  911): acquireWL(42e75e18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  911): releaseWL(42e75e18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,D/AutoSetting( 1327): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3883): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3883): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3883): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3883): Cust_ConnectToPC   : spcsc>false
D/        ( 3883): Cust_ConnectToPC   : IPT>true
D/        ( 3883): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3883): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3883): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3883): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3883): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,I/PSReceiver( 3883): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  911): startDataStallAlarm: tag=20586 delay=15s
,I/ClockThread( 1119): stop update clock
I/SmartNS_PSService( 3883): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3883): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
,I/SmartNS_PSService( 3883):  defaultType:0
V/NotificationService(  911): batLight: plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c80000
D/qdlights(  911): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:On
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  911):    returned true
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/NotificationService(  911): batLight: plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c80000
,D/qdlights(  911): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  911): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  911): doBoolean: SignalStrength 97
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,V/SRS_Proc(  369): ParamSet string: screen_state=on
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  911):    returned true
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  911): updateScreenOn: false
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4823 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): acquireWL(4341d808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4341d808): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42db5ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOn: 1454063378612
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOn: 1454063378613
D/PMS     (  911): releaseWL(42db5ab8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073af8
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42073af8, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@436c3218
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
W/ContextImpl( 4823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): acquireWL(42b55450): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/PMS     (  911): acquireWL(4361bc88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4823 1000 null
,D/SmartSyncUtils( 4823): isEpsOn(), nState = 0
D/PMS     (  911): releaseWL(42b55450): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20586 mDataStallAlarmIntent=PendingIntent{423cea30: PendingIntentRecord{4245c1d8 android broadcastIntent}}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
I/AlarmManager(  911): [AlarmQueuing] wifi connection: true
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
D/WifiNative-wlan0(  911): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  911):    returned true,
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  369): ParamSet string: screen_state=off
D/PMS     (  911): acquireWL(42a58700): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
D/PMS     (  911): releaseWL(4361bc88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/SmartSyncUtils( 4823): getMobilePolicyEnabled, result = true
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  911):    returned true
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  911): releaseWL(42a58700): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl( 4823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4823): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4823): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4823): isEpsOn(), nState = 0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@436c3218
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@436c3218, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
D/WifiService(  911): New client listening to asynchronous messages
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@436c3218, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@436c3218
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@436c43b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@436c43b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1550): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): acquireWL(432ea3f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(432ea3f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43703d58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm: null
,D/PMS     (  911): releaseWL(43703d58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOff
,D/AutoSetting( 1327): service - mHandler: cancel location update
,D/AutoSetting( 1327): service -           changes count: 0
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1491): service - handleMessage() stop self
,D/AutoSetting( 1491): service - onDestroy() END
,D/AutoSetting( 1491): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4429
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4429:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4429
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=4001
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 4001:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4001
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1327): service - mHandler: update timezone
,D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1491): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1491): service - onCreate()
W/ActivityManager(  911): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector,
D/AutoSetting( 1491): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1491): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1491): service - mHandler: update timezone
,D/DotMatrix( 1550): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  911): batLight: plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c80000
D/qdlights(  911): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1491): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1491): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1491): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1491): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1550): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41c5de38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 2 11
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(43a58f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42535220: PendingIntentRecord{43309c70 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124830, Int=0
,D/PMS     (  911): releaseWL(43a58f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43917740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=25 [4][1][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(43474b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43474b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43917740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(434fcad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(434fcad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43af1cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): acquireWL(4330acf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43e1d880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1454063395546 tag=VacuumService
,D/PMS     (  911): releaseWL(43af1cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4330acf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43a437c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
,D/PMS     (  911): releaseWL(43e1d880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(43a437c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43a38810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  911): releaseWL(43a38810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): acquireWL(43a1d260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(43a1d260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(43a07108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(43a07108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4391b528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561,
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): acquireWL(43905c88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(43905c88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(436736a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4391b528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425598d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(425598d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 2146 seconds from now (1454063396349)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =1bf0 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  911): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  911): releaseWL(436736a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4256e648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(4256e648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4256e900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2873 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  911): doString: SIGNAL_POLL
W/WifiHW  (  911): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024695
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024884
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025063
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025067
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025072
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026458
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360026472
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360029561
,D/PMS     (  911): releaseWL(4256e900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424f8a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{420a5f30: PendingIntentRecord{422f8d78 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=129546, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(424f8a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(423ef838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(423ef838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  911): updateBatteryInfo
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
,D/UsbnetService(  911): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=98
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(435b3b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(435b3b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{434288c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  911): acquireWL(42634338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42cc4f00: PendingIntentRecord{43719a18 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138322, Int=0
,D/AutoSetting( 1327): service - handleMessage() stop self
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2873/10029)
D/PMS     (  911): releaseWL(42634338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1327): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=4451
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Killing 4451:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/AutoSetting( 1327): service - handleMessage() quit looper
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,I/ActivityManager(  911): Recipient 4451
,D/PMS     (  911): acquireWL(423bcbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{424e8d18: PendingIntentRecord{424e8ce0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142058, Int=0
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(42451158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(423bcbe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =9b90 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=243
D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  911): [NET] getaddrinfo_proxy-, success
I/global  (  911): call createSocket() return a new socket.
D/libc    (  911): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  911): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  911): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  911): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  911):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  911): releaseWL(42451158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/AutoSetting( 1491): service - handleMessage() stop self
,D/AutoSetting( 1491): service - onDestroy() END
,D/AutoSetting( 1491): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=4484,
,I/ActivityManager(  911): Killing 4484:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 4484
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(434d5c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{420a5f30: PendingIntentRecord{422f8d78 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=189545, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(434d5c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(42dcc918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42dcc918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1550): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1550): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  911): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  911): acquireWL(42438168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42438168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(41a92f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{424dcd38: PendingIntentRecord{43889a70 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=210763, Int=0
,D/PMS     (  911): releaseWL(41a92f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ClearcutLoggerApiImpl( 2873): disconnect managed GoogleApiClient
,D/PMS     (  911): acquireWL(438e5a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10027}
,V/AlarmManager(  911): sending alarm PendingIntent{4262ad48: PendingIntentRecord{43889a70 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228196, Int=0
,D/PMS     (  911): releaseWL(438e5a98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(42dc5bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{420a5f30: PendingIntentRecord{422f8d78 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=249546, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42dc5bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(4393e6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(4393e6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4543): --= Surplus to requirements =--
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): ****TEST TOOK:  ms ****
I/jxcore-log( 4543): 
,I/jxcore-log( 4543): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4543): 
,E/cutils-trace( 4878): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4878): ====startRecUseTime====
D/htc.customization.log.level( 4878):  is 
,W/CustomizationLogLevel( 4878): Level value is invalid, use default level 2
,D/CustomizationManager( 4878):  Read ACC file spent 0.118 (s)
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4878): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4878): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4878): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4878): Parsing tag category name = system
,I/CustomizationCIDLoader( 4878): Parsing tag category name = application
I/CustomizationCIDLoader( 4878): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4878): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4878): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4878): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4878): Parsing tag category name = Settings
D/CustomizationManager( 4878):  Read CID file spent 0.170 (s)
,D/CustomizationManager( 4878):  All configurations done spent 0.170 (s)
W/HtcNativeFlag( 4878): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4878): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4878): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4878): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  911): deletePackageAsUser: pkg=com.test.thalitest, pid=4878, uid=2000 user=0
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  911): killProcessQuiet, pid=4543
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  911): Killing 4543:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  911):   Force finishing activity ActivityRecord{43871848 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  911): Copying FileAsset 0x6c7f6cd8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1211): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 4543 uid 10389
,W/PackageSettings(  911): Skipping PackageSetting{421c8e00 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  911): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/dalvikvm-heap( 4150): Grow heap (frag case) to 16.947MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,D/DotMatrix( 1550): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
,D/DotMatrix( 1550): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1550): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/PMS     (  911): acquireWL(42549d08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42549d08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AccTypeManager( 1368): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/InputDispatcher(  911): channel '42dc60a8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  911): channel '42dc60a8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  911): Attempted to unregister already unregistered input channel '42dc60a8 com.test.thalitest.MainActivity (s)'
I/WindowState(  911): WIN DEATH: Window{42dc60a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  911): Client connection lost with reason: 4
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowManager(  911): WINDOW DIED Window{42dc60a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1368): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1368): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,I/[PluginManager]RegisterService( 1327): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/[PluginManager]RegisterService( 1327): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,E/ExternalAccountType( 1368): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
,I/IcingCorporaProvider( 2844): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  911):   Scheme: "smsto"
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4894 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  911): acquireWL(438da0b8): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2844): UpdateCorporaTask done [took 191 ms] updated apps [took 191 ms] 
,W/PackageManager(  911): Unable to load service info ResolveInfo{41bb0118 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4894): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4894): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4894): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4894): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4894): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4894): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4894): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4894): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4894): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4894): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4894): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4894): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4894): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4894): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4894): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4894): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4894): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4894): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4894): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4894): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4894): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4894): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4894): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4894): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4894): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4894): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4894): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4894): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4894): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4894): threadid=11: thread exiting with uncaught exception (group=0x4166de30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4894): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4894): Process: com.google.android.apps.docs, PID: 4894
E/AndroidRuntime( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4894): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4894): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4894): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4894): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4894): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4894): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4894): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4894): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4894): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4894): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4894): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4894): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4894): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4894): Opened ClientFlag.db in read-only mode
D/Process ( 4894): killProcess, pid=4894
D/Process ( 4894): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4913 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  911): Skipping deliver [background] BroadcastRecord{423373f8 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42397188 4894 com.google.android.apps.docs/10100/u0 remote:42419568}: process crashing
I/ActivityManager(  911): Recipient 4894
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4894) has died.
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4913): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4913): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4913): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4913): threadid=10: thread exiting with uncaught exception (group=0x4166de30)
E/AndroidRuntime( 4913): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4913): Process: com.android.keychain, PID: 4913
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
E/AndroidRuntime( 4913): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4913): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4913): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  911): App crashed! Process: com.android.keychain
,D/Process ( 4913): killProcess, pid=4913
,D/Process ( 4913): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4926 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454063565741.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
,I/ActivityManager(  911): Recipient 4913
,I/ActivityManager(  911): Process com.android.keychain (pid 4913) has died.
,W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AppTag  ( 4926): getInstance(Context context)
,D/AppTag  ( 4926): getInstance(Context context)
,D/AppTag  ( 4926): onCreate()
,D/PMS     (  911): acquireWL(42df28f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4150 10160 null
,D/PMS     (  911): releaseWL(42df28f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  911): killProcessQuiet, pid=4498
,W/dalvikvm( 4175): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 4498:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 4498
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PackageBroadcastService( 2182): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2182): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2182): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2182): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2182): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2182): Module APK com.google.android.play.games already loaded
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2182): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2182): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e8b1b20
,W/dalvikvm( 2182): threadid=38: thread exiting with uncaught exception (group=0x4166de30)
,E/SQLiteLog( 2182): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2182): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca99518
,E/DriveAsyncService( 2182): disk I/O error (code 3850)
E/DriveAsyncService( 2182): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2182): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2182): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2182): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2182): 	at java.lang.Thread.run(Thread.java:864)
,I/LocationSettingsChecker( 2182): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  911): App crashed! Process: com.google.android.gms
,D/Process ( 2182): killProcess, pid=2182
,D/Process ( 2182): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2182): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2182): Process: com.google.android.gms, PID: 2182
E/AndroidRuntime( 2182): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2182): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2182): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2182): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2182): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2182): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2182): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2182): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2182): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): handleWLDeath(438da0b8): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  911): Client connection lost with reason: 4
,I/ActivityManager(  911): Recipient 2182
,I/ActivityManager(  911): Process com.google.android.gms (pid 2182) has died.
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10997ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10997ms
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20997ms
,E/SQLiteLog( 2873): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 2873): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fb2b50
,W/dalvikvm( 2873): threadid=1: thread exiting with uncaught exception (group=0x4166de30)
,E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 2873): FATAL EXCEPTION: main
E/AndroidRuntime( 2873): Process: com.google.process.gapps, PID: 2873
E/AndroidRuntime( 2873): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2873): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2873): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2873): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2873): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2873): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2873): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2873): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2873): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2873): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2873): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2873): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2873): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2873): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2873): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2873): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2873): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2873): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2873): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2873): 	... 10 more
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
,D/Process ( 2873): killProcess, pid=2873
,D/Process ( 2873): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4959 uid=10098 gids={50098, 3003, 5012}
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2873
,D/WifiService(  911): Client connection lost with reason: 4
,I/ActivityManager(  911): Process com.google.process.gapps (pid 2873) has died.
,I/DeviceManagement( 4959): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4959 dbg=false s=true
,I/DeviceManagement( 4959): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4959): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30894ms
I/DeviceManagement( 4959): WorkflowService: Starting workflow service
I/DeviceManagement( 4959): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ace100] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4959): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4959): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4959): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4959): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4973 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4959): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4959): SessionStateController: Checking invariants...
,D/Documents( 4973): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4973): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4973): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4973): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4973): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4973): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4973): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4973): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4973): threadid=1: thread exiting with uncaught exception (group=0x4166de30)
I/ActivityManager(  911): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4987 uid=10023 gids={50023, 1028, 1015, 1023}
E/AndroidRuntime( 4973): FATAL EXCEPTION: main
E/AndroidRuntime( 4973): Process: com.android.documentsui, PID: 4973
E/AndroidRuntime( 4973): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4973): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4973): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4973): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4973): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4973): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4973): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4973): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4973): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4973): 	... 10 more
,I/ActivityManager(  911): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4999 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  911): Killing 4114:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  911): killProcessQuiet, pid=4114
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  911): App crashed! Process: com.android.documentsui
,D/Process (  911): killProcessQuiet, pid=3966
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  911): Killing 3966:com.google.android.music:main/u0a154 (adj 15): empty #17
,E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454063566378.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
,I/ActivityManager(  911): Recipient 3966
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  911): Client com.google.android.music (pid 3966): Died!
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,D/Process ( 4973): killProcess, pid=4973
D/Process ( 4973): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b30d10 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,D/ExternalStorage( 4987): After updating volumes, found 1 active roots
,W/ContentService(  911): Found dead observer, removing
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4973
I/ActivityManager(  911): Process com.android.documentsui (pid 4973) has died.
,W/dalvikvm( 4999): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4999): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4999): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4999): install
,I/MultiDex( 4999): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4999): loading existing secondary dex files
,I/MultiDex( 4999): load found 3 secondary dex files
,I/MultiDex( 4999): install done
,E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4959): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4959): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4959): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4959): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4959): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ace100]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4959): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4959): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4959): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4959): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4959): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4959): WorkflowService: Stopping workflow service
I/ActivityManager(  911): Recipient 4114
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5016 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}

```
