#### Test 506502785b2d2b2_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4549): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4549): ====startRecUseTime====
D/htc.customization.log.level( 4549):  is 
W/CustomizationLogLevel( 4549): Level value is invalid, use default level 2
D/CustomizationManager( 4549):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4549): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4549): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4549): Parsing tag category name = system
I/CustomizationCIDLoader( 4549): Parsing tag category name = application
I/CustomizationCIDLoader( 4549): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4549): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4549): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4549): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4549): Parsing tag category name = Settings
D/CustomizationManager( 4549):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4549):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4549): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4549): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4549): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4549): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4549
D/PMS     (  906): acquireHCC(42a81430): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(424e3288): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x69dfaf90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1126363168
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c56258
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/PMS     (  906): acquireWL(41fd74c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4560 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4560): Copying FileAsset 0x5c83a428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4560): Binding Chromium to main looper Looper (main, tid 1) {41ab0770}
I/LibraryLoader( 4560): Expected native library version number "",actual native library version number ""
I/chromium( 4560): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4560): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4201dc38:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4560): 1101816232: getState(). Returning 12
D/PMS     (  906): acquireWL(420c3fa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(420966c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(420c3fa8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4560): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4560): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4560): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4560): Local Branch: 
I/Adreno-EGL( 4560): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4560): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4560):                  aa63bbd948f41d15fc72f585e
W/chromium( 4560): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4560): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4560): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4560): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4560): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4560): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4560): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4560): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4560): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4560): CordovaWebView is running on device made by: HTC
,W/AwContents( 4560): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1268
,W/ResourceType( 4560): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4560): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41af7858, mServedView=org.apache.cordova.engine.SystemWebView{41abd4c0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4560): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +257ms
,I/InputMethodManagerService(  906): Enable input method client, pid=4560
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(41fd74c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4560): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4560): JniHelper::setJavaVM(0x41581048), pthread_self() = 1662224168
,D/JX-Cordova( 4560): jxcore cordova android initializing
I/ActivityManager(  906): Waited long enough for: ServiceRecord{440f3f00 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 11.556MB for 96598-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 11.605MB for 144892-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 13.173MB for 1100216-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 14.056MB for 1650320-byte allocation
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 15.434MB for 2475476-byte allocation
,I/SensorManager(  906): mEventCount = 1200
,D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4560): Grow heap (frag case) to 17.463MB for 3713210-byte allocation
,D/PMS     (  906): acquireWL(41aa7db8): PARTIAL_WAKE_LOCK  Icing 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(41aa7db8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(423720f8): PARTIAL_WAKE_LOCK  Icing 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(423720f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4344a690): PARTIAL_WAKE_LOCK  Icing 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(4344a690): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(424392c8): PARTIAL_WAKE_LOCK  Icing 0x1 2574 10028 null
,W/jxcore-log( 4560): Initializing JXcore engine
,W/jxcore-log( 4560): JXcore engine is ready
D/PMS     (  906): releaseWL(424392c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42a81430): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 4560): Starting JXcore engine
D/PMS     (  906): releaseHCC(424e3288): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4560): Platform android
W/jxcore-log( 4560): 
,W/jxcore-log( 4560): Process ARCH arm
W/jxcore-log( 4560): 
,I/jxcore-log( 4560): JXcore Cordova bridge is ready!
I/jxcore-log( 4560): 
,W/jxcore-log( 4560): JXcore engine is started
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/chromium( 4560): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(420966c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4607 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(422fc100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{42535c88: PendingIntentRecord{4255af40 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450579266595, Int=60000
,D/PMS     (  906): releaseWL(422fc100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4607): SMSBackupAgentService started
,D/SMSBackup( 4607): Checking restore status
D/SMSBackup( 4607): Restore complete
,D/SMSBackup( 4607): cancelCheckAlarm
,D/SMSBackup( 4607): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3703
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3703:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3703
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4560): Toggling radios to true
I/jxcore-log( 4560): 
,D/BluetoothAdapter( 4560): enable(): BT is already enabled..!
,D/WifiManager( 4560): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1318
,W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
,D/WifiManager( 4560): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4560, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4560): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): TDLS: Tear down peers
I/wpa_supplicant( 1178): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4560): Radios toggled
I/jxcore-log( 4560): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4560): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4560): 
I/jxcore-log( 4560): Perf Test app loaded loaded
I/jxcore-log( 4560): 
I/Choreographer( 4560): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4560): check test folder
I/jxcore-log( 4560): 
,I/jxcore-log( 4560): found test : ./testFindPeers.js
I/jxcore-log( 4560): 
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1178): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1178): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
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
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8784bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1178): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  906):    returned true
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  906): acquireWL(42405b88): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
I/jxcore-log( 4560): found test : ./testSendData.js
I/jxcore-log( 4560): 
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): Fast associate: Old scan results
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19374 mDataStallAlarmIntent=PendingIntent{423d65e0: PendingIntentRecord{4233a0b8 android broadcastIntent}}
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(43f7e628): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/libc    (  364): [NET] entry_id:6   entry:0xb6fac220  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb6fabd90  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb6fac8f8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb6fac7d0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb6fac310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb6fac428  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb6fabf40  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb6fac0e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb6fac4f0  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb6fabe40  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(437ccad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  906): acquireWL(4233f3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1359/10028)
D/PMS     (  906): releaseWL(43f7e628): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(4233f3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): releaseWL(437ccad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/chromium( 4560): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(424ea3a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED,
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  906): ipv4Default null
,I/Tethering(  906): No IPv4 upstream interface, giving up.
I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4450/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4450/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4629 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(424ea3a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4629): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4629): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4629): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4629): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4629): Preparing secondary program dexes.
V/DexLibLoader( 4629): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4629): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4629): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4629): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4629): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4629): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4629): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4629): Dex already copied
D/OdexVerifier( 4629): Odex verification is skipped.
,V/DexLibLoader( 4629): Creating class loader
,V/DexLibLoader( 4629): Finished creating class loader
V/DexLibLoader( 4629): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4629): Dex already copied
D/OdexVerifier( 4629): Odex verification is skipped.
,V/DexLibLoader( 4629): Creating class loader
,V/DexLibLoader( 4629): Finished creating class loader
V/DexLibLoader( 4629): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4629): Dex already copied
D/OdexVerifier( 4629): Odex verification is skipped.
,V/DexLibLoader( 4629): Creating class loader
V/DexLibLoader( 4629): Finished creating class loader
V/DexLibLoader( 4629): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4629): Dex already copied
D/OdexVerifier( 4629): Odex verification is skipped.
,V/DexLibLoader( 4629): Creating class loader
,V/DexLibLoader( 4629): Finished creating class loader
,V/DexLibLoader( 4629): Verifying classes from secondary dexes.
,D/DexLibLoader( 4629): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4629): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1178): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1178): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
I/wpa_supplicant( 1178): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1178): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-91
I/wpa_supplicant( 1178): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-91
I/wpa_supplicant( 1178): [NULL] 10:9a:dd:8e:22:d9 freq=2462 level=-91
D/wpa_supplicant( 1178): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1178): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1178): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1178): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1178): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1178): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1178): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1178): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1178): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1,178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 1
I/wpa_supplicant( 1178): wpa_s->is_screen_on 1
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 1
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87864e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
,I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb87864e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb8785718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8785718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (1317) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000107001209
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-50
I/wpa_supplicant( 1178): tsf=0000000107001225
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-77
I/wpa_supplicant( 1178): tsf=0000000021471262
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1178): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-84
I/wpa_supplicant( 1178): tsf=0000000107001237
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=UPC4688432
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-50
I/wpa_supplicant( 1178): tsf=0000000107001221
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1178): freq=2462
I/wpa_supplicant( 1178): level=-89
I/wpa_supplicant( 1178): tsf=0000000107001242
I/wpa_supplicant( 1178): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=UPC Wi-Free
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1178): freq=2462
I/wpa_supplicant( 1178): level=-89
I/wpa_supplicant( 1178): tsf=0000000107001245
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=UPC0039325
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1178): freq=2462
I/wpa_supplicant( 1178): level=-91
I/wpa_supplicant( 1178): tsf=0000000107001249
I/wpa_supplicant( 1178): flags=[WPA-EAP-CCMP+T
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 107001209, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 107001225, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 21471262, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 107001237, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 107001221, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 107001242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 107001245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (10) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 107001249, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 8: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 107001253, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 9: scan result = SSID: Apple AirPort, BSSID: 10:9a:dd:8e:22:d9, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2462, timestamp: 107001256, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 10 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4629): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4629): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Connect event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1178): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Add randomness: count=16 entropy=9
I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on association
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1178): EAPOL: enable timer tick
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): Get randomness: len=32 entropy=10
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
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
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4,:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87859f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    broadcast key
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1178): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1178): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1178): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1178): set send_ind_to_ndc = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1178): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1178): EAPOL authentication completed successfully
I/wpa_supplicant( 1178): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
E/FbInjectorInitializer( 4629): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 1
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43aa9a08): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4629): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4629): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4629): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3329
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3329:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3329
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43c0dc10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,D/PMS     (  906): acquireWL(43ff76d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(43c0dc10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/PMS     (  906): releaseWL(43ff76d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4658 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,W/fb4a(:<default>):UserScope( 4629): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4629): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4658): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4658): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4629): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4672 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3991
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3991:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4689 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4392
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 4629): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4629): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ActivityManager(  906): Killing 4392:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/dalvikvm( 4629): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4629): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4629): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4629): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4629): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4629): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4629): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4629): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4629): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/ActivityManager(  906): Recipient 4392
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 3991
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 9.961MB for 84664-byte allocation
,W/dalvikvm( 4629): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4629): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4629): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4629): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4629): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4629): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4629): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 4689): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 9.977MB for 28144-byte allocation
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 10.092MB for 79892-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,V/WebViewChromiumFactoryProvider( 4689): Binding Chromium to main looper Looper (main, tid 1) {41aa94e8}
,I/LibraryLoader( 4689): Expected native library version number "",actual native library version number ""
,I/chromium( 4689): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4689): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(4320bfc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): acquireWL(4321d140): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4689): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(4320bfc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4689): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4689): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4689): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4689): Local Branch: 
I/Adreno-EGL( 4689): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4689): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4689):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4689): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
,D/Process (  906): killProcessQuiet, pid=4148
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4148:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4148
,I/dalvikvm-heap( 4629): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434094e0 u0 ReceiverList{434093c0 4629 com.facebook.katana/10026/u0 remote:4332b7c8}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434094e0 u0 ReceiverList{434093c0 4629 com.facebook.katana/10026/u0 remote:4332b7c8}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43aa8f98 u0 ReceiverList{43a9e660 4629 com.facebook.katana/10026/u0 remote:4376e0e8}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/PMS     (  906): acquireWL(43a7ae30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): releaseWL(43a7ae30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1421): Unknown pending intent to remove.
D/wpa_supplicant( 1178): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1178): EAPOL: disable timer tick
D/PMS     (  906): acquireWL(42595e20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
D/PMS     (  906): releaseWL(42595e20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(43aa9a08): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
,D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19376 delay=15s
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = true<<<<<
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423dbc30
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(436604e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/PMS     (  906): acquireWL(437f9fe8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(43a93a30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
D/PMS     (  906): releaseWL(437f9fe8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 2574): Preparing to send checkin request
,I/EventLogService( 2574): Accumulating logs since 1450579218965
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2574): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2574): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/PMS     (  906): releaseWL(436604e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bd2310 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4764 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4764): install
,I/MultiDex( 4764): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4764): loading existing secondary dex files
,I/MultiDex( 4764): load found 1 secondary dex files
,I/MultiDex( 4764): install done
,I/ProviderInstaller( 4764): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4764): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4764/10028)
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(42405b88): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(438d51a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4450/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/acms    ( 1884): Checking Certificates
I/acms    ( 1884): Checking Developer Certificates
,I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
,I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
,I/acms    ( 1884): Updating next query delay: 75600000
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1884): cancelACMSProgrammedChecks
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4375d6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/PMS     (  906): releaseWL(4375d6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(438d51a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (4044/10051)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4450/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(41f91ab0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(41f91ab0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(4239c598): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10028 null
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1281 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1396): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1396): service - handleMessage() setting current location null
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,I/dalvikvm-heap( 4315): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 294
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(4247b0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/PMS     (  906): releaseWL(4247b0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1359): Connected
D/PMS     (  906): acquireWL(42558968): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(4239c598): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
,I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4560): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(42558968): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(41d27928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
,W/dalvikvm( 4560): threadid=1: thread exiting with uncaught exception (group=0x41679e30)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4560): FATAL EXCEPTION: main
E/AndroidRuntime( 4560): Process: com.test.thalitest, PID: 4560
E/AndroidRuntime( 4560): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4560): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4560): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4560): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4560): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4560): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4560): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4560): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4560): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4560): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4560): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4560): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4560): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4560): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4560): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4560): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4560): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4560): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4560): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  906): acquireWL(43727d70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,W/asset   (  906): Copying FileAsset 0x6ed8a100 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1359): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(42443728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/PMS     (  906): releaseWL(42443728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(41d27928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/CheckinTask( 2574): Sending checkin request (8887 bytes)
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2574): [NET] getaddrinfo-,err=8
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2574): [NET] getaddrinfo-, 1
,D/libc    ( 2574): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3789 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 268
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2574): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=15 [13][2][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2574): [NET] getaddrinfo-,err=8
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42101820
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
,W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42101820, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421d9068
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@425da1d0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/PMS     (  906): Going to sleep due to screen timeout...
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #0: color=#0
W/PMS     (  906): mWirelessDisplayManager is null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{42019430 u0 com.test.thalitest/.MainActivity t2 f}
,D/PMS     (  906): acquireWL(43f40fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(43f40fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 415ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/PMS     (  906): acquireWL(424f4240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424f4240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=4560
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43a97e98)
,D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1256): applyRouting -2
D/PMN     (  906): wakingUp
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): acquireWL(43045350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(43045350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/FeedHostManager( 1268): [onResume]
,I/FeedProviderManager( 1268): onResume
I/SocialFeedProvider( 1268): +onResume
I/SocialFeedProvider( 1268): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1268): -onResume
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PMN     (  906): onScreenOn
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast,
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/MtpService( 2000): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/NfcService( 1256): applyRouting - 0
,D/MtpService( 2000): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting -2
D/PMS     (  906): runPSCheck
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1268/10075)
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): acquireWL(425c00d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  906): releaseWL(425c00d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4337): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4337): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4337): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4337): Cust_ConnectToPC   : spcsc>false
D/        ( 4337): Cust_ConnectToPC   : IPT>true
D/        ( 4337): Cust_ConnectToPC   : Singel_USB>false
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Settings( 4337): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4337): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4337): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4337): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19377 delay=15s
,I/PSReceiver( 4337): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/SmartNS_PSService( 4337): onReceive:android.intent.action.USER_PRESENT
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:On
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/Settings( 4337): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/SmartNS_PSService( 4337):  defaultType:0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,V/SRS_Proc(  371): ParamSet string: screen_state=on
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/WifiNative-wlan0(  906):    returned true
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4811 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/PMS     (  906): releaseWL(43727d70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,I/ClockThread( 1117): stop update clock
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/Process (  906): killProcessQuiet, pid=4420
,I/ActivityManager(  906): Killing 4420:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  906): Recipient 4420
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(4321d140): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/fb4a(:<default>):UserScope( 4629): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4629): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(43211be0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4811 1000 null
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1816): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1816): onScreenOn: 1450579273650
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1816): onScreenOn: 1450579273650
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
D/PMS     (  906): acquireWL(44000520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
D/PMS     (  906): releaseWL(44000520): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bda170 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421d9068
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421d9068, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@425da1d0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/RemoteViews.Performance( 1117): com.google.android.gms 4 12 3 12
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43ff9940): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,I/FeedHostManager( 1268): [onPause]
,I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c56258
I/SocialFeedProvider( 1268): +onPause
,I/SocialFeedProvider( 1268): -onPause
D/PMS     (  906): releaseWL(43211be0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19377 mDataStallAlarmIntent=PendingIntent{424fa350: PendingIntentRecord{4233a0b8 android broadcastIntent}}
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:Off
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43382d28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43ff9940): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/SmartSyncUtils( 4811): getMobilePolicyEnabled, result = true
V/SRS_Proc(  371): ParamSet string: screen_state=off
I/CheckinTask( 2574): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2574): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
D/NetworkPolicy(  906): updateScreenOn: false
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=4450
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): releaseWL(43382d28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  906): Killing 4450:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4811): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): releaseWL(43a93a30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2574): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c937a0 that was originally bound here
E/ActivityThread( 2574): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c937a0 that was originally bound here
E/ActivityThread( 2574): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2574): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2574): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2574): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2574): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2574): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2574): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2574): 	at bks.a(SourceFile:298)
E/ActivityThread( 2574): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2574): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2574): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2574): 	at java.lang.Thread.run(Thread.java:864)
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425da1d0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425da1d0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425da1d0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425da1d0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1243): start background delete task...
D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425da6e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425da6e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ActivityManager(  906): Recipient 4450
,D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,I/GCM     ( 1359): GCM config loaded
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1816): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1816): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1816): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1816): disableBatteryAlarm: null
D/PMS     (  906): acquireWL(43acfe48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
,D/PMS     (  906): releaseWL(43acfe48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1816): onScreenOff
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,E/fb4a(:<default>):LocalFbBroadcastManager( 4629): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a308 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86,
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4689): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(42549828): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): acquireWL(43762580): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1421 10028 null
,D/PMS     (  906): releaseWL(42549828): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43762580): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  906): killProcessQuiet, pid=4474
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4474:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4474
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4492
,D/AutoSetting( 1507): service - handleMessage() quit looper
I/ActivityManager(  906): Killing 4492:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4492
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  906): Activity destroy timeout for ActivityRecord{42019430 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(44051630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(44051630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): service - onCreate()
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e7b558 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 5 2 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/PMS     (  906): acquireWL(43a90830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42290f40: PendingIntentRecord{424878a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140884, Int=0
D/PMS     (  906): acquireWL(43a8c1d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41fd9268: PendingIntentRecord{42479c98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141112, Int=0
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): releaseWL(43a90830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(4389d068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1479 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
D/PMS     (  906): releaseWL(4389d068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43a8c1d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=4044
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4044:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4044
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43fff710 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(43320ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43320ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4437
,I/ActivityManager(  906): Killing 4437:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4437
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4310b8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4310b8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42f61dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end,
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42f61dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  906): acquireWL(42616ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42616ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424a4670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{437680d8: PendingIntentRecord{435bf070 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228061, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4853 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4231b310: PendingIntentRecord{4256a8d8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450579382872, Int=10800000
,D/PMS     (  906): releaseWL(424a4670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4853/10047)
,D/Process (  906): killProcessQuiet, pid=4509
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4509:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4509
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/PMS     (  906): acquireWL(41e25840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41e25840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4247fc00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{423f65b8: PendingIntentRecord{435bf070 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230994, Int=0
,D/PMS     (  906): releaseWL(4247fc00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42160de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42160de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(423c3e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423c3e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4205c560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): releaseWL(4205c560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42600420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42600420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/GLSActivity( 1359): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1359): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1359): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1359): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1359): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1359): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1359): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1359): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b11560 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4280): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4280): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4280): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4280): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4280): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4280): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4280): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4280): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 15 4 12
,D/libc    ( 4280): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4280): [NET] getaddrinfo-,err=8
D/libc    ( 4280): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4280): [NET] getaddrinfo-, 1
,D/libc    ( 4280): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7c2b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 4
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4280): [NET] getaddrinfo_proxy-, success
I/global  ( 4280): call createSocket() return a new socket.
D/libc    ( 4280): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4280): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4280): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4280): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(424162f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(424162f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43514fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43514fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process ( 4560): killProcess, pid=4560
,D/Process ( 4560): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  906): Disable input method client, pid=4560
,I/ActivityManager(  906): Recipient 4560
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  906): channel '422c2a48 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '422c2a48 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '422c2a48 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  906): Process com.test.thalitest (pid 4560) has died.
I/WindowState(  906): WIN DEATH: Window{422c2a48 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
I/WindowManager(  906): WINDOW DIED Window{422c2a48 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PMS     (  906): acquireWL(425df4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425df4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42465870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42465870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42ffc4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ffc4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43f6eef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43f6eef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42e86de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e86de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43a89678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a89678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440eb728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440eb728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43b64bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b64bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425c7db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425c7db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43068310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43068310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4259a718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4252ddd8: PendingIntentRecord{43147780 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410741, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{433d5670: PendingIntentRecord{42498420 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450579763489, Int=1800000
,D/PMS     (  906): acquireWL(43bc6b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(4259a718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4314dfd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(43bc6b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2574): Aggregate from 1450579271213 (log), 1450577963427 (data)
,D/PMS     (  906): releaseWL(4314dfd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  906): acquireWL(43278e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43278e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete,
,D/PMS     (  906): acquireWL(43fa3fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fa3fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a9cff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43a9cff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43566400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(43566400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus,
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Disconnect event
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1178): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
I/wpa_supplicant( 1178): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1178): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8784bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1178): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19378 mDataStallAlarmIntent=null
D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/PMS     (  906): acquireWL(431e62d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: SET pno 1
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1178): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:1   entry:0xb6fac410  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb6fac830  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb6fac108  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb6fabea0  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb6fa79d0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(43722148): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(43c17d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(43af7ee8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1359/10028)
D/PMS     (  906): releaseWL(43c17d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(43722148): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1178): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: SCAN
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  906):    returned true
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(43af7ee8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(43fe5000): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  906): releaseWL(43fe5000): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/PMS     (  906): acquireWL(42bdebe8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,D/PMS     (  906): acquireWL(4376d248): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(42bdebe8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
D/PMS     (  906): releaseWL(4376d248): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1396): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): service - onCreate()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  906): request 4230eed8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,I/dalvikvm-heap( 4315): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4315): Grow heap (frag case) to 16.951MB for 1821008-byte allocation
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=17 entropy=0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): No APs found - clear blacklist and try again
E/wpa_supplicant( 1178): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1178): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=18 entropy=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1178): State: DISCONNECTED -> INACTIVE
D/WifiNative-wlan0(  906): doBoolean: SET pno 1
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1",
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
,D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@425b7c38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@425b7c38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@425b7c38 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1178): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (121) for get BSS: id=10
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000682021725
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (1) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 682021725, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 1 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b9dcc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{421e06b0: PendingIntentRecord{425272c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450579846323, Int=0
,D/PMS     (  906): releaseWL(42b9dcc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4280): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4280): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4280): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4280): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4280): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1178): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
,D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000,
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
,I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:1,
D/WifiNative-wlan0(  906):    returned true
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=19 entropy=2
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=20 entropy=3
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE,
D/WifiNative-wlan0(  906): doBoolean: SET pno 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
,D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1178): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (121) for get BSS: id=10
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000688041516
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (1) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 688041516, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 1 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1178): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN",
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  906):    returned true,
D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter,
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:2,
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=21 entropy=4
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=22 entropy=5
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiNative-wlan0(  906): doBoolean: SET pno 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 75,
D/wpa_supplicant( 1178): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (121) for get BSS: id=10
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000694345447
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 694345447, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 1 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (1) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43214338 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1178): Add randomness: count=23 entropy=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 11
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87864e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
,I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb87864e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6,
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb8785718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8785718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1178): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (240) for get BSS: id=10
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000694345447
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-50
I/wpa_supplicant( 1178): tsf=0000000696327763
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ####
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 694345447, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (2) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 696327763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 2 to mScanResults
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43807a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697314, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43807a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e2b8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{425952a0: PendingIntentRecord{438feae0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450579861464, Int=0
,D/PMS     (  906): releaseWL(42e2b8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4280): [1] 5.onFinished: Installation state replication succeeded.
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Connect event
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1178): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1178): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18,
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 0,
D/HTCRequest(  906): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  906): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  906): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  906): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700,
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
D/WifiStateMachine(  906): Enter handleAssociateRejectEvent
D/WifiStateMachine(  906): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
,D/WifiStateMachine(  906): Exit handleAssociateRejectEvent,
,D/WirelessDisplayService(  906): HANDLE_WIFI_DIS,
D/WirelessDisplayService(  906): HANDLE_STOP_DIS
,D/WirelessDisplayService(  906): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  906): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING,
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=24 entropy=7
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): No APs found - clear blacklist and try again
E/wpa_supplicant( 1178): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1178): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1178): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=25 entropy=8
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): clear disabled list - type=1
I/wpa_supplicant( 1178): No suitable network found
W/wpa_supplicant( 1178): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1178): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (240) for get BSS: id=10
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000694345447
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=11
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-50
I/wpa_supplicant( 1178): tsf=0000000696327763
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 694345447, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 696327763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 2 to mScanResults
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (2) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/PMS     (  906): acquireWL(43b25610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b25610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43a1a9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43a1a9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): releaseWL(431e62d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  906): acquireWL(43bc6118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc6118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a709d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42a709d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43478948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4252ddd8: PendingIntentRecord{43147780 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710741, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{41da34e0: PendingIntentRecord{423e63e8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786592, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): releaseWL(43478948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(43212568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43212568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43219360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43219360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f48bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43f48bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4345f638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4345f638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425e3f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425e3f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bce8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bce8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431dd070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431dd070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b89538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b89538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431eb558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431eb558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b24fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b24fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bc0950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc0950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4912 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  906): acquireWL(437cc778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10075}
,V/AlarmManager(  906): sending alarm PendingIntent{425f5668: PendingIntentRecord{438db9c8 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{424bc018: PendingIntentRecord{425aaa18 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450580103202, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42438880: PendingIntentRecord{437b85a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450580173739, Int=0
,W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4811): call getInstance()
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(437cc778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4811): MY_DEBUG = false
D/PMS     (  906): acquireWL(43277088): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4811 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4811): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4811): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4811): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4811): SettingOnTime = 1450591200000, randomSettingOnTime = 1450588158000
,D/SmartSyncScreenOnOffTimeReceiver( 4811): SettingOffTime = 1450656000000, randomSettingOffTime = 1450661687000
,D/SmartSyncScreenOnOffTimeReceiver( 4811): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4811): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4811): bNightModeTurnOffOnce = false
D/PMS     (  906): acquireWL(43b17d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/AlarmManager(  906): sending alarm PendingIntent{432b4be8: PendingIntentRecord{4319fa70 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450580173809, Int=0
W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43277088): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartSyncUtils( 4811): getMobilePolicyEnabled, result = true
D/SmartSyncDataLinkTurnOffService( 4811): turnOffMobile bPolicyEnabled = true
D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4811): isWifiHotSpotEnabled = false
D/SmartSyncDataLinkTurnOffService( 4811): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  906): getProviders()=[gps, network]
D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4811): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4811): isCharging status = 5
,I/ImageRamCache( 4912): create image Cache, size: 31457280.
,D/SmartSyncDataLinkTurnOffService( 4811): turnOffWifi ui setting = true
I/ImageRamCache( 4912): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4912): create image Cache, size: 12582912.
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/PMS     (  906): releaseWL(43b17d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/FeedSettings( 4912): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4912): GroupBudget 0.500000 0.380000
I/FeedSettings( 4912): GroupBudget 60 45 15
D/SmartSyncUtils( 4811): isWifiHotSpotEnabled = false
I/Prism.ExternalStringMa_( 4912): changeLocale(): en_GB
D/SmartSyncUtils( 4811): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4811): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4811): turnOffWifi bWifiConnected = false
D/LocationManagerService(  906): getProviders()=[gps, network]
D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4811/1000)
D/SmartSyncDataLinkTurnOffService( 4811): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4811): isCharging status = 5
I/Prism.AllAppsOptionsMa_( 4912): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4912): loadGridSize() with Alternative
,D/libc    ( 4912): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4,
D/libc    ( 4912): [NET] getaddrinfo-,err=8
D/libc    ( 4912): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4912): [NET] getaddrinfo-, 1
,D/libc    ( 4912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f418 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =f418 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=f418, total retry = 3 times, errno=111,v_circuit=0-----,
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 4912): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 4912): Exception on getConfig()
W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4523
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4523:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4523
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4248a3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4248a3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42454890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42454890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431f71f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431f71f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424ca8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424ca8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-49
D/wpa_supplicant( 1178): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1178): Add randomness: count=26 entropy=9
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-49
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 12
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87864e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
,I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb87864e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb8785718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8785718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification ,- portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1178): reply (119) for get BSS: id=12
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-49
I/wpa_supplicant( 1178): tsf=0000001084729889
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (1) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 2412, timestamp: 1084729889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 1 to mScanResults
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Connect event
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1178): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Add randomness: count=27 entropy=10
I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on association
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1178): EAPOL: enable timer tick
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): Get randomness: len=32 entropy=11
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent,
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87859f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  906): updateConnectedAP...
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    broadcast key
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1178): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1178): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE,
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1178): set send_ind_to_ndc = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1178): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1178): EAPOL authentication completed successfully
I/wpa_supplicant( 1178): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...,
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1178): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42b6a540): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 1
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1178): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1178): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1178): EAPOL: disable timer tick,
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0,
,I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0,
D/PMS     (  906): releaseWL(42b6a540): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1178): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/wpa_supplicant( 1178): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true,
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent,
,D/WifiWatchdogStateMachine(  906): WAN detection
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423dbc30
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/WifiStateMachine(  906): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(43fbc4a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/PMS     (  906): acquireWL(43ff33b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,D/PMS     (  906): acquireWL(440b4348): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): releaseWL(43ff33b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,I/CheckinService( 2574): Preparing to send checkin request
,I/EventLogService( 2574): Accumulating logs since 1450579763532
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2574): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2574): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43fbc4a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f705e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 3 10 3 12
,W/Settings( 4764): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4764/10028)
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/PMS     (  906): acquireWL(432e6038): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(432e6038): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42437340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/acms    ( 1884): Checking Certificates
I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1884): Checking Developer Certificates
I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1884): Updating next query delay: 75600000
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1884): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState,
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=100 [1][1][0]
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0,
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(42437340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,I/CheckinTask( 2574): Sending checkin request (8960 bytes)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2574): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2574): [NET] getaddrinfo-, 1
,D/libc    ( 2574): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/libc    (  364): [NET] +++++ res_nsend xid =b270 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(425c1018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/PMS     (  906): releaseWL(425c1018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =1a4b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
D/PMS     (  906): acquireWL(43ab3248): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10028 null
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2574): [NET] getaddrinfo_proxy-, success
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1396): service - onCreate()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1396): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  906): request 4230eed8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2574): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(434e98f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/PMS     (  906): releaseWL(434e98f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1359): Connected
D/PMS     (  906): acquireWL(43ba2528): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(43ab3248): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(43ba2528): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43152870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1359): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/PMS     (  906): releaseWL(43152870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(431aeee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(431aeee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(4370cd08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(4370cd08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=10 [20][2][0]
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f992b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 8 3 12
,I/CheckinTask( 2574): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2574): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/PMS     (  906): releaseWL(440b4348): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2574): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41af0aa8 that was originally bound here
E/ActivityThread( 2574): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41af0aa8 that was originally bound here
E/ActivityThread( 2574): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2574): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2574): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2574): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2574): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2574): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2574): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2574): 	at bks.a(SourceFile:298)
E/ActivityThread( 2574): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2574): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2574): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2574): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1359): GCM config loaded
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d9c6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86,
,D/PMS     (  906): acquireWL(44041d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(44041d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43a5b378 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(43ba3580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ba3580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1507): service - mHandler: update timezone
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b0b528 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  906): acquireWL(43a9db50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43a9db50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44062e78 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/PMS     (  906): acquireWL(4376a698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4376a698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43516d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43516d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435142a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435142a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431dc908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431dc908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42579c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42579c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4248ec40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4248ec40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4389d520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4389d520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41d69cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41d69cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4230c388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4230c388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41ebda30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41ebda30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43067c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1357313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43067c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4254f1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(4254f1a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4379a910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4379a910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Disconnect event
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1178): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
I/wpa_supplicant( 1178): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1178): TDLS: Remove peers on disassociation
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8784bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1178): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(424c3960): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19379 mDataStallAlarmIntent=null
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: SET pno 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '74 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 74 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1178): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '75 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 75 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] entry_id:2   entry:0xb6fa78f0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb6fb0f68  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb6fac548  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(437998b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(43232a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): acquireWL(43406fb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
,D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I//system/bin/ip(  364): RTNETLINK answers: No such process
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1359/10028)
D/PMS     (  906): releaseWL(43232a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(437998b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1178): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  906):    returned true
D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(43406fb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/NativeDaemonConnector.ResponseQueue(  906): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  906): Removing request: null (7)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:2
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(440ffae0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/PMS     (  906): releaseWL(440ffae0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/PMS     (  906): acquireWL(43ad2658): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,D/PMS     (  906): acquireWL(4216efd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
,D/PMS     (  906): releaseWL(43ad2658): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028),
D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/PMS     (  906): releaseWL(4216efd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1396): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): service - onCreate()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  906): request 4230eed8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1178): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1178): Failed to initiate AP scan
,I/wpa_supplicant( 1178): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1178): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1178): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=28 entropy=0
D/wpa_supplicant( 1178): Add randomness: count=29 entropy=1
D/wpa_supplicant( 1178): Add randomness: count=30 entropy=2
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1178): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1178):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1178): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1178): No APs found - clear blacklist and try again
E/wpa_supplicant( 1178): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1178): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/WifiNative-wlan0(  906): doBoolean: SET pno 1
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_conne,cted is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 0
I/wpa_supplicant( 1178): wpa_s->is_screen_on 0
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 12
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87864e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb87864e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb8785718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8785718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb8785718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supp,licant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1178): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1178): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1178): reply (383) for get BSS: id=12
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-53
I/wpa_supplicant( 1178): tsf=0000001404571742
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=13
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000001404571719
,I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=14
I/wpa_supplicant( 1178): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-79
I/wpa_supplicant( 1178): tsf=0000001404571752
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1178): ssid=DIRECT-qjWorkCentre 3025
,I/wpa_supplicant( 1178): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 1404571742, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1404571719, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 1404571752, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): nl80211: Event message available,
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1178): nl80211: Connect event
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1178): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5,
,D/wpa_supplicant( 1178): Add randomness: count=31 entropy=3
I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on association
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1178): EAPOL: enable timer tick
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
,I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=1, interval=30
,D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
,I/wpa_supplicant( 1178): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1178): Get randomness: len=32 entropy=4
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700,
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87859f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1178):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
E/wpa_supplicant( 1178): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1178): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1178): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1178): set send_ind_to_ndc = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1178): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1178): EAPOL authentication completed successfully
I/wpa_supplicant( 1178): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 4337): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4337): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 1
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1178): nl80211: Event message available
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1178): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1178): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43b44ad8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423042e0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(43b44ad8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState,
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423dbc30
D/WISPrService( 4337): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/wpa_supplicant( 1178): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1178): EAPOL: disable timer tick
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
,D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(43ff2e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43466ac0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/PMS     (  906): acquireWL(432768c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2574 10028 null
D/PMS     (  906): releaseWL(43466ac0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,I/CheckinService( 2574): Preparing to send checkin request
,I/EventLogService( 2574): Accumulating logs since 1450580250152
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2574): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2574): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
,D/PMS     (  906): releaseWL(43ff2e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d562a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 8 3 12
,W/Settings( 4764): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4764/10028)
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4764): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4764): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4764): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4764): Local Branch: 
I/Adreno-EGL( 4764): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4764): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4764):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  906): releaseWL(424c3960): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/wpa_supplicant( 1178): environment dirty rate=50 [2][1][0]
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43b252a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1884): Checking Certificates
I/acms    ( 1884): Checking Developer Certificates
I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1884): Updating next query delay: 75600000
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1884): cancelACMSProgrammedChecks
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1421/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4658/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4009/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
I/NetworkMonitor( 4009): type=WIFI subType= reason=null isConnected=true
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(438b7d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/PMS     (  906): releaseWL(438b7d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/PMS     (  906): releaseWL(43b252a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/CheckinTask( 2574): Sending checkin request (8962 bytes)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2000/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2574): [NET] getaddrinfo-,err=8
D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2574): [NET] getaddrinfo-, 1
D/libc    ( 2574): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b3a0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4629/10026)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43a603d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2574 10028 null
D/PMS     (  906): releaseWL(43a603d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/GCM     ( 1359): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/PMS     (  906): acquireWL(43279b10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10028 null
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =590a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2574): [NET] getaddrinfo_proxy-, success
,D/MobileConnectivityChangeReceiver( 4658): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4658): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1396): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4315/10160)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1847/10178)
,D/libc    ( 2574): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2574): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/PMS     (  906): acquireWL(425e40d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(425e40d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1359): Connected
D/PMS     (  906): acquireWL(431dd0f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(43279b10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): releaseWL(431dd0f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4389b438): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1359): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10028)
D/PMS     (  906): acquireWL(43c10728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
D/PMS     (  906): releaseWL(43c10728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(4389b438): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  906): acquireWL(437fa980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10028 null
,D/PMS     (  906): releaseWL(437fa980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2574/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=25 [20][5][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2574/10028)
,W/GLSUser ( 1359): GoogleAccountDataService.getToken()
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1359): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1359): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2574): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bf3718 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 8 3 12
,I/CheckinTask( 2574): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2574): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2574/10028)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(432768c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2574): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b0b5b8 that was originally bound here
E/ActivityThread( 2574): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b0b5b8 that was originally bound here
E/ActivityThread( 2574): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2574): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2574): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2574): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2574): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2574): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2574): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2574): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2574): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2574): 	at bks.a(SourceFile:298)
E/ActivityThread( 2574): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2574): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2574): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2574): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1359): GCM config loaded
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2019 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/PMS     (  906): acquireWL(43f97628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1417314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f97628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43b13b70 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(43231f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43231f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41aeb8a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 4 9 4 11
,D/PMS     (  906): acquireWL(43baece0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43baece0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4376f060 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/PMS     (  906): acquireWL(43b9ad88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1477313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b9ad88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435d7ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  906): sending alarm PendingIntent{41da34e0: PendingIntentRecord{423e63e8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506632, Int=0
,D/PMS     (  906): releaseWL(435d7ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(43726d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(43726d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43449428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1537314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43449428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bf6a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43bf6a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bf0240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43bf0240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ad0640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1597313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ad0640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(432bd6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(432bd6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b54b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b54b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43324760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1657313, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43324760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fe10a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fe10a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c24e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c24e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f64980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1717314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f64980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42354980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42354980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(438cc860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(438cc860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42604450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1777314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42604450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fea590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43fea590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(431ae9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(431ae9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42bb65a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1837313, Int=0
,I/ProcessStatsService(  906): Prepared write state in 37ms
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42bb65a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440a2550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(440a2550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43beed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43beed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43adc8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232aa90: PendingIntentRecord{4234df18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897314, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43adc8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5104): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5104): ====startRecUseTime====
D/htc.customization.log.level( 5104):  is 
W/CustomizationLogLevel( 5104): Level value is invalid, use default level 2
D/CustomizationManager( 5104):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5104): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5104): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5104): Parsing tag category name = system
I/CustomizationCIDLoader( 5104): Parsing tag category name = application
I/CustomizationCIDLoader( 5104): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5104): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5104): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5104): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5104): Parsing tag category name = Settings
D/CustomizationManager( 5104):  Read CID file spent 0.157 (s)
D/CustomizationManager( 5104):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 5104): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5104): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5104): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5104): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=5104, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4607
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4607:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
W/asset   (  906): Copying FileAsset 0x630495a8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  906): Skipping PackageSetting{42236a50 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/ActivityManager(  906): Recipient 4607
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
D/PMS     (  906): acquireWL(421fde98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
W/GeofencerStateMachine( 1421): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/acms    ( 1884): Unregistering com.test.thalitest
E/acms    ( 1884): Could not unregister removed application com.test.thalitest
D/PMS     (  906): releaseWL(421fde98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/Prism.ItemManager( 4912): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 4912): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2574): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5119 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 5119): install
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/ActivityManager(  906): Delaying start of: ServiceRecord{44124710 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 5119): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5119): loading existing secondary dex files
I/MultiDex( 5119): load found 1 secondary dex files
I/MultiDex( 5119): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5136 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2574): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2574, uid=10028, userID:0
I/Icing   ( 2574): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(43be25b8): PARTIAL_WAKE_LOCK  Icing 0x1 2574 10028 null
D/PMS     (  906): releaseWL(43be25b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 5119): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 5136): install
I/MultiDex( 5136): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5136): loading existing secondary dex files
I/MultiDex( 5136): load found 1 secondary dex files
I/MultiDex( 5136): install done
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 5136): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2959): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5157 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2959): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2959): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635809d0
W/dalvikvm( 2959): threadid=15: thread exiting with uncaught exception (group=0x41679e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/SQLiteDatabase( 5119): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5119): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 5119): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 5119): 	at ctn.run(SourceFile:985)
E/AndroidRuntime( 2959): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2959): Process: com.google.android.googlequicksearchbox:search, PID: 2959
E/AndroidRuntime( 2959): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2959): 	at cid.d(PG:186)
E/AndroidRuntime( 2959): 	at clo.g(PG:594)
E/AndroidRuntime( 2959): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2959): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2959): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2959): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2959): 	at clr.tL(PG:827)
E/AndroidRuntime( 2959): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2959): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2959): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5119): threadid=12: thread exiting with uncaught exception (group=0x41679e30)
D/Process ( 2959): killProcess, pid=2959
D/Process ( 2959): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 5119): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5119): Process: com.google.android.gms.drive, PID: 5119
E/AndroidRuntime( 5119): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5119): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5119): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5119): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5119): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 5119): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 5119): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5119): killProcess, pid=5119
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5119): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 2959
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2959) has died.
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2959): Died!
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/ActivityManager(  906): Recipient 5119
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 5119) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10897ms
E/SQLiteDatabase( 5157): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5157): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5157): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5157): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5157): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5157): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5157): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5157): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5157): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5157): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5157): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5157): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5157): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5157): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5157): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5157): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5157): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5157): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5157): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5157): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5157): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5157): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5157): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5157): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5157): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5157): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5157): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5157): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5157): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5157): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5157): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5157): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5157): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5157): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5157): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5157): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5157): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5157): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5157): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5157): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5157): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5157): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5157): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5157): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5157): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5157): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5157): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5157): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5157): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5157): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5157): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5157): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5157): threadid=11: thread exiting with uncaught exception (group=0x41679e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5157): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5157): Process: com.google.android.apps.docs, PID: 5157
E/AndroidRuntime( 5157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5157): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5157): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5157): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5157): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5157): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5157): killProcess, pid=5157
D/Process ( 5157): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5177 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 5157
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 5157) has died.
W/ContextImpl( 5177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5177): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5177): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5177): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5190 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
W/dalvikvm( 5177): threadid=10: thread exiting with uncaught exception (group=0x41679e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5177): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5177): Process: com.android.keychain, PID: 5177
E/AndroidRuntime( 5177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5177): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5177): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5177): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5177): killProcess, pid=5177
D/Process ( 5177): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450581076222.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 5177
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 5177) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10365ms
D/AppTag  ( 5190): getInstance(Context context)
D/AppTag  ( 5190): getInstance(Context context)
D/AppTag  ( 5190): onCreate()
W/PackageManager(  906): Unable to load service info ResolveInfo{43510ed0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  906): acquireWL(43f74310): PARTIAL_WAKE_LOCK  AsyncService 0x1 4315 10160 null
D/PMS     (  906): releaseWL(43f74310): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Prism.ItemManager( 4912): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4912): loadItems() com.htc.launcher.pageview.WidgetManager@41b19958 +
I/Prism.WidgetManager( 4912): onLoadItems() +
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5208 uid=10098 gids={50098, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=4853
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4853:com.htc.aurora/u0a47 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4853
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41b3ce10 +
I/Prism.WidgetManager( 1268): onLoadItems() +
I/DeviceManagement( 5208): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5208 dbg=false s=true
I/DeviceManagement( 5208): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5208): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5208): WorkflowService: Starting workflow service
I/DeviceManagement( 5208): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ad7ed8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5208): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5208): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5208): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5208): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5222 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5208): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5208): SessionStateController: Checking invariants...
D/Documents( 5222): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5222): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5222): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5222): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5222): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5222): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5222): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5222): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5222): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5222): threadid=1: thread exiting with uncaught exception (group=0x41679e30)
D/Process (  906): killProcessQuiet, pid=4912
E/AndroidRuntime( 5222): FATAL EXCEPTION: main
E/AndroidRuntime( 5222): Process: com.android.documentsui, PID: 5222
E/AndroidRuntime( 5222): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5222): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5222): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5222): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5222): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5222): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5222): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5222): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5222): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5222): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5222): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5222): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5222): 	... 10 more
I/ActivityManager(  906): Killing 4912:com.htc.launcher:biclient/u0a75 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  906): App crashed! Process: com.android.documentsui
D/Documents( 5222): Loading roots for com.android.externalstorage.documents
D/GCM     ( 1359): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450581076549.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5237 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process ( 5222): killProcess, pid=5222
D/Process ( 5222): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 5222
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.documentsui (pid 5222) has died.
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  906): Failure sending broadcast Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/BroadcastQueue(  906): android.os.TransactionTooLargeException
W/BroadcastQueue(  906): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  906): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  906): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)

```
