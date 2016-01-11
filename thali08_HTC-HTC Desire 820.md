#### Test 55613145e2b298d_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{442fc0d0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1119): WifiActivity: 1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4391): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4391): ====startRecUseTime====
D/htc.customization.log.level( 4391):  is 
W/CustomizationLogLevel( 4391): Level value is invalid, use default level 2
D/CustomizationManager( 4391):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4391): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4391): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4391): Parsing tag category name = system
I/CustomizationCIDLoader( 4391): Parsing tag category name = application
I/CustomizationCIDLoader( 4391): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4391): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4391): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4391): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4391): Parsing tag category name = Settings
D/CustomizationManager( 4391):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4391):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4391): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4391): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4391): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4391
D/PMS     (  906): acquireHCC(42129d80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42086870): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6c460b50 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1110085936
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420ab518
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  906): acquireWL(41b7e498): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4402 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4402): Copying FileAsset 0x5c70e428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4402): Binding Chromium to main looper Looper (main, tid 1) {41a8ddd8}
I/LibraryLoader( 4402): Expected native library version number "",actual native library version number ""
I/chromium( 4402): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4402): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422beea0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): acquireWL(423bbc60): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  906): acquireWL(42300b50): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
D/PMS     (  906): releaseWL(42300b50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4402): 1101676584: getState(). Returning 12
I/Adreno-EGL( 4402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4402): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4402): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4402): Local Branch: 
I/Adreno-EGL( 4402): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4402): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4402):                  aa63bbd948f41d15fc72f585e
W/chromium( 4402): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4402): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4402): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4402): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4402): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4402): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4402): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4402): CordovaWebView is running on device made by: HTC
,W/AwContents( 4402): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1273
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +268ms
,W/ResourceType( 4402): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4402): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad56d8, mServedView=org.apache.cordova.engine.SystemWebView{41a9b340 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/InputMethodManagerService(  906): Enable input method client, pid=4402
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(41b7e498): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/JsMessageQueue( 4402): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4402): JniHelper::setJavaVM(0x41565048), pthread_self() = 1663003912
,D/JX-Cordova( 4402): jxcore cordova android initializing
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.543MB for 64402-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.590MB for 96598-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.669MB for 144892-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.786MB for 217334-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 11.961MB for 325996-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 12.642MB for 733480-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 13.243MB for 1100216-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 14.112MB for 1650320-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 15.486MB for 2475476-byte allocation
,I/dalvikvm-heap( 4402): Grow heap (frag case) to 17.507MB for 3713210-byte allocation
,W/jxcore-log( 4402): Initializing JXcore engine
,W/jxcore-log( 4402): JXcore engine is ready
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42129d80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(42086870): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4402): Starting JXcore engine
,D/PMS     (  906): acquireWL(42fd9158): PARTIAL_WAKE_LOCK  Icing 0x1 2253 10028 null
,D/PMS     (  906): releaseWL(42fd9158): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(41fcbd40): PARTIAL_WAKE_LOCK  Icing 0x1 2253 10028 null
,D/PMS     (  906): releaseWL(41fcbd40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(422c85a0): PARTIAL_WAKE_LOCK  Icing 0x1 2253 10028 null
,D/PMS     (  906): releaseWL(422c85a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(440351f0): PARTIAL_WAKE_LOCK  Icing 0x1 2253 10028 null
,D/PMS     (  906): releaseWL(440351f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/jxcore-log( 4402): Platform android
W/jxcore-log( 4402): 
,W/jxcore-log( 4402): Process ARCH arm
W/jxcore-log( 4402): 
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4451 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(43f5fdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{425919b0: PendingIntentRecord{425b40e0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452523235220, Int=60000
,D/PMS     (  906): releaseWL(43f5fdb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4451): SMSBackupAgentService started
,D/SMSBackup( 4451): Checking restore status
D/SMSBackup( 4451): Restore complete
,D/SMSBackup( 4451): cancelCheckAlarm
,D/SMSBackup( 4451): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3093
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3093:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3093
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/jxcore-log( 4402): JXcore Cordova bridge is ready!
I/jxcore-log( 4402): 
,W/jxcore-log( 4402): JXcore engine is started
,I/Choreographer( 4402): Skipped 139 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4402): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(423bbc60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=54 rxSum=40} preTxRxSum={txSum=53 rxSum=39}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20147 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20148 delay=15s
,I/jxcore-log( 4402): Toggling radios to true
I/jxcore-log( 4402): 
D/PMS     (  906): acquireWL(42e17d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41ebea28: PendingIntentRecord{42480118 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106272, Int=0
,D/PMS     (  906): releaseWL(42e17d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/BluetoothAdapter( 4402): enable(): BT is already enabled..!
,D/WifiManager( 4402): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
,W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1285
W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4402, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
D/WifiManager( 4402): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4402): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): TDLS: Tear down peers
I/wpa_supplicant( 1179): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4402): Radios toggled
I/jxcore-log( 4402): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4402): Received device characteristics:
I/jxcore-log( 4402): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4402): Bluetooth name: HTC Desire 820
I/jxcore-log( 4402): Device name: HTC-HTC Desire 820
I/jxcore-log( 4402): 
I/jxcore-log( 4402): Perf Test app loaded loaded
I/jxcore-log( 4402): 
I/Choreographer( 4402): Skipped 91 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4402): check test folder
I/jxcore-log( 4402): 
,I/jxcore-log( 4402): found test : ./testFindPeers.js
I/jxcore-log( 4402): 
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1179): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1179): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7147bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1179): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Ignore disconnect event triggered during reassociation
I/jxcore-log( 4402): found test : ./testSendData.js
I/jxcore-log( 4402): 
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/PMS     (  906): acquireWL(43670578): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): Fast associate: Old scan results
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20148 mDataStallAlarmIntent=PendingIntent{42363748: PendingIntentRecord{42480118 android broadcastIntent}}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  906):    returned true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
,D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:5   entry:0xb8a13818  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8a12fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8a13108  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8a136f0  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8a132e0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8a13410  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8a135a0  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(43fe6ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  906): acquireWL(41b3e580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): acquireWL(4255a5c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/PMS     (  906): releaseWL(41b3e580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1179): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1370/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(43fe6ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  906): releaseWL(4255a5c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4402): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1479/10028)
D/PMS     (  906): acquireWL(4319b708): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3868): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1896/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3868/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4474 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(4319b708): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4474): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4474): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4474): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4474): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk,
V/DexLibLoader( 4474): Preparing secondary program dexes.
,V/DexLibLoader( 4474): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4474): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4474): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4474): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4474): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4474): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4474): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4474): Dex already copied
D/OdexVerifier( 4474): Odex verification is skipped.
,V/DexLibLoader( 4474): Creating class loader
,V/DexLibLoader( 4474): Finished creating class loader
V/DexLibLoader( 4474): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4474): Dex already copied
D/OdexVerifier( 4474): Odex verification is skipped.
,V/DexLibLoader( 4474): Creating class loader
,V/DexLibLoader( 4474): Finished creating class loader
V/DexLibLoader( 4474): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4474): Dex already copied
D/OdexVerifier( 4474): Odex verification is skipped.
,V/DexLibLoader( 4474): Creating class loader
V/DexLibLoader( 4474): Finished creating class loader
V/DexLibLoader( 4474): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4474): Dex already copied
D/OdexVerifier( 4474): Odex verification is skipped.
,V/DexLibLoader( 4474): Creating class loader
,V/DexLibLoader( 4474): Finished creating class loader
,V/DexLibLoader( 4474): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4474): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4474): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4474): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4474): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/SensorManager(  906): mEventCount = 1050
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1179): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1179): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1179): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1179): [NULL] 44:e9:dd:10:c0:ab freq=2437 level=-91
D/wpa_supplicant( 1179): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1179): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1179): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1179): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1179): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1179): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1179): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[3] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1179): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 3
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa,_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 1
I/wpa_supplicant( 1179): wpa_s->is_screen_on 1
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): selected network = 1
D/wpa_supplicant( 1179): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb71494e8  current_ssid=0x0
D/wpa_supplicant( 1179): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1179): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1179): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1179): check if in concurrent case
,I/wpa_supplicant( 1179): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1179): RSN: PMKSA cache search - network_ctx=0xb71494e8 try_opportunistic=0
D/wpa_supplicant( 1179): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1179): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1179): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1179): nl80211: Unsubscribe mgmt frames handle 0xb7148718 (mode change)
D/wpa_supplicant( 1179): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7148718
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718,
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7148718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1179):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179):   * freq=2412
D/wpa_supplicant( 1179):   * Auth Type 0
D/wpa_supplicant( 1179):   * WPA Versions 0x2
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1179): nl80211: Connect request send successfully
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (928) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-47
I/wpa_supplicant( 1179): tsf=0000000108611507
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
,I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-52
I/wpa_supplicant( 1179): tsf=0000000108611526
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-52
I/wpa_supplicant( 1179): tsf=0000000108611522
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1179): ssid=01ABC
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2452
I/wpa_supplicant( 1179): level=-77
I/wpa_supplicant( 1179): tsf=0000000108611532
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-84
I/wpa_supplicant( 1179): tsf=0000000108611536
I/wpa_supplicant( 1179): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC Wi-Free
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=5
I/wpa_supplicant( 1179): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-84
I/wpa_supplicant( 1179): tsf=0000000108611541
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=UPC5999698
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=6
I/wpa_supplicant( 1179): bssid=44:e9:dd:10:c0:ab
I/wpa_supplicant( 1179): freq=2437
I/wpa_supplicant( 1179): level=-91
I/wpa_supplicant( 1179): tsf=0000000108611546
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=FunBox2-C0AB
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108611507, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 108611526, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 108611522, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 108611532, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 108611536, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 108611541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: FunBox2-C0AB, BSSID: 44:e9:dd:10:c0:ab, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 108611546, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
,D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/fb4a(:<default>):StaticBindingVerifier( 4474): Verify
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1179): nl80211: Event message available
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1179): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Connect event
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1179): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Add randomness: count=16 entropy=7
I/wpa_supplicant( 1179): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on association
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1179): EAPOL: enable timer tick
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): Get randomness: len=32 entropy=8
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48,
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb71489f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0cb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    broadcast key
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1179): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1179): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1179): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1179): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1179): set send_ind_to_ndc = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1179): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1179): EAPOL authentication completed successfully
I/wpa_supplicant( 1179): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 1
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43471628): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4230c098 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4230c098 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4474): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4474): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4230
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4230:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  906): acquireWL(436cc418): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2253 10028 null
I/ActivityManager(  906): Recipient 4230
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(43ec4598): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2253 10028 null
D/PMS     (  906): releaseWL(436cc418): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,D/GCM     ( 1370): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(43ec4598): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4496 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/AutoSetting( 1396): service - onCreate()
D/AutoSetting( 1396): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  906): request 424d23d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4474): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4474): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4474): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4496): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4496): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4519 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4536 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3847
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3847:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4536): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 9.973MB for 28144-byte allocation
E/dalvikvm( 4474): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4474): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4474): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4474): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4474): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4474): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4474): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4474): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4474): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Recipient 3847
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/dalvikvm( 4474): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4474): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4474): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4474): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4474): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4474): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4474): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4474): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4474): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 10.041MB for 39954-byte allocation
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 10.118MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,V/WebViewChromiumFactoryProvider( 4536): Binding Chromium to main looper Looper (main, tid 1) {41a93248}
,I/LibraryLoader( 4536): Expected native library version number "",actual native library version number ""
,I/chromium( 4536): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4536): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43527bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
,D/PMS     (  906): acquireWL(43636c18): PARTIAL_WAKE_LOCK  AudioMix 0x1 375 1013 null
,E/AudioManagerAndroid( 4536): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(43527bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG (),
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4536): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4161/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4161/10160)
,D/Process (  906): killProcessQuiet, pid=4000
,I/ActivityManager(  906): Killing 4000:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4474): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440005e8 u0 ReceiverList{43fe4f80 4474 com.facebook.katana/10026/u0 remote:43fccc48}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440005e8 u0 ReceiverList{43fe4f80 4474 com.facebook.katana/10026/u0 remote:43fccc48}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42fe9f58 u0 ReceiverList{42fe9f18 4474 com.facebook.katana/10026/u0 remote:42e0f4f8}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/PMS     (  906): acquireWL(434c0dc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1479 10028 null
,D/PMS     (  906): releaseWL(434c0dc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1479): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43f7d508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1479 10028 null
D/PMS     (  906): releaseWL(43f7d508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 4000
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/wpa_supplicant( 1179): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1179): EAPOL: disable timer tick
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43471628): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1179): WiFi gateway: 0x101a8c0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20150 delay=15s
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4181): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
,D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c0228
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
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
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(43b305e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43ff5660): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2253 10028 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
D/PMS     (  906): acquireWL(440caee8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2253 10028 null
D/PMS     (  906): releaseWL(43ff5660): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 2253): Preparing to send checkin request
I/EventLogService( 2253): Accumulating logs since 1452523186874
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2253): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2253): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2253/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2253/10028)
,D/PMS     (  906): releaseWL(43b305e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420ac800
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420ac800, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42282678
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42368530
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 394ms
,W/dalvikvm( 4402): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/PMS     (  906): acquireWL(43650de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,W/dalvikvm( 4402): threadid=1: thread exiting with uncaught exception (group=0x4165de30)
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43650de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/AndroidRuntime( 4402): FATAL EXCEPTION: main
E/AndroidRuntime( 4402): Process: com.test.thalitest, PID: 4402
E/AndroidRuntime( 4402): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4402): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4402): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4402): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4402): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4402): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4402): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4402): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4402): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4402): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4402): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4402): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4402): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4402): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4402): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4402): 	at dalvik.system.NativeStart.main(Native Method)
,D/ActivityManager(  906): screenshot for ActivityRecord{420306f0 u0 com.test.thalitest/.MainActivity t2}, bitmap=android.graphics.Bitmap@42432128, time = 450
,W/PMS     (  906): mWirelessDisplayManager is null
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/NfcService( 1258): ScreenObserver: OFF
,D/NfcService( 1258): applyRouting - 0
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
I/InputMethodManagerService(  906): Disable input method client, pid=4402
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/NfcService( 1258): applyRouting -2
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(4364d4f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
D/PMS     (  906): releaseWL(4364d4f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): acquireWL(435448a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,W/asset   (  906): Copying FileAsset 0x62781890 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425cb458)
D/PMN     (  906): wakingUp
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20151 delay=15s
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:On
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  375): ParamSet string: screen_state=on
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
D/MtpService( 2448): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1258): applyRouting - 0
,D/MtpService( 2448): [MTP][onReceive]-
D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1258): applyRouting -2
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): acquireWL(422cb080): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): releaseWL(422cb080): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  906): updateScreenOn: false
,I/ClockThread( 1119): stop update clock
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4181): Cust_ConnectToPC   : spcsc>false
D/        ( 4181): Cust_ConnectToPC   : IPT>true
,D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4181): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4181): onReceive:android.intent.action.USER_PRESENT
,W/CheckinRequestBuilder( 2253): awaiting user notification for token
,I/SmartNS_PSService( 4181): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4181):  defaultType:0
W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41be0878 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 9 5 12
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4623 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4635 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1787): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): onScreenOn: 1452523242560
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1787): onScreenOn: 1452523242561
D/PMS     (  906): releaseWL(43670578): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
D/PMS     (  906): acquireWL(422e6cd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
D/PMS     (  906): releaseWL(422e6cd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42282678
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42282678, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42368530
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,I/MultiDex( 4635): install
,I/MultiDex( 4635): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(4200c098): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): releaseWL(435448a8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/MultiDex( 4635): loading existing secondary dex files
,I/MultiDex( 4635): load found 1 secondary dex files
,I/MultiDex( 4635): install done
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/PMS     (  906): acquireWL(424b9a20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1896/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
I/acms    ( 1896): Checking Certificates
I/acms    ( 1896): Checking Developer Certificates
I/acms    ( 1896): Checking Application Certificates
I/acms    ( 1896): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1896): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1896): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1896): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1896): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1896): Updating next query delay: 75600000
I/mlserverapp( 1896): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1896): cancelACMSProgrammedChecks
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3868): type=WIFI subType= reason=null isConnected=true
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1479/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3868/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
D/PMS     (  906): releaseWL(424b9a20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3921/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4623): isEpsOn(), nState = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/PMS     (  906): acquireWL(4202ef20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4623 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20151 mDataStallAlarmIntent=PendingIntent{424ec560: PendingIntentRecord{42480118 android broadcastIntent}}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(43a02c08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): acquireWL(43fb4800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/ProviderInstaller( 4635): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:Off
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4202ef20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): releaseWL(43fb4800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/SRS_Proc(  375): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4623): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=4262
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Killing 4262:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4262
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1246): start background delete task...
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43a02c08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{420306f0 u0 com.test.thalitest/.MainActivity t2 f}
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=4292
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 4292:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42c6b7e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2253 10028 null
,I/ActivityManager(  906): Recipient 4292
D/PMS     (  906): releaseWL(42c6b7e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1787): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): onScreenOff
,D/GCM     ( 1370): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1787): onScreenOff
D/PMS     (  906): acquireWL(43f7ba80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
D/PMS     (  906): releaseWL(43f7ba80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,D/PMS     (  906): acquireWL(425f5200): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1370 10028 null
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1370): [NET] getaddrinfo-, 1
D/libc    ( 1370): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =35f4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/AutoSetting( 1396): service - mHandler: cancel location update
D/AutoSetting( 1396): service -           changes count: 0
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1396): service - onStartCommand() screen is off, don't request location
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 260
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1370): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4161/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4161/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4623): isEpsOn(), nState = 0
D/SmartSyncUtils( 4623): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4623): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42368530
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42368530, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42368530, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/GCM     ( 1370): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42368530
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425c2f70 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425c2f70 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/fb4a(:<default>):UserScope( 4474): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4474): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1370): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): acquireWL(430e8300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  906): releaseWL(430e8300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/GCM     ( 1370): Connected
D/PMS     (  906): acquireWL(4400f1e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(425f5200): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(4400f1e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(434d6348): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4474): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1370): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  906): releaseWL(434d6348): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4407e360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  906): releaseWL(4407e360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4474/10026)
,D/PMS     (  906): releaseWL(43636c18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/Settings( 4635): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [3][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4635): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4635): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4635): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4635): Local Branch: 
I/Adreno-EGL( 4635): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4635): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4635):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4635): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4635): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4635): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4635): Local Branch: 
I/Adreno-EGL( 4635): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4635): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4635):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4635): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4635): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4635): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4635): Local Branch: 
I/Adreno-EGL( 4635): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4635): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4635):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4635/10028)
,I/CheckinTask( 2253): Sending checkin request (8840 bytes)
D/libc    ( 2253): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2253): [NET] getaddrinfo-,err=8
D/libc    ( 2253): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2253): [NET] getaddrinfo-, 1
,D/libc    ( 2253): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fa7e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2253): [NET] getaddrinfo_proxy-, success
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1246): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    ( 2253): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2253): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(434c9638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c6e5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/PMS     (  906): releaseWL(434c9638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/CheckinResponseProcessor( 2253): From server: 0 gservices updates and 1 deletes
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,I/CertBlacklister(  906): Certificate blacklist changed, updating...
,I/CertBlacklister(  906): Certificate blacklist updated
,I/GservicesProvider( 1370): main difference update completed
,I/ActivityManager(  906): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4683 uid=10016 gids={50016, 3003, 5012, 2001}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2253/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2253/10028)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=13 [23][3][0]
,W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4683): Update started
,E/UpdateRequestReceiver( 4683): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,I/UpdateFetcherService( 4683): Update started
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2253): awaiting user notification for token
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41c398d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 9 3 12
,I/CheckinTask( 2253): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2253): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,D/PMS     (  906): releaseWL(440caee8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2253): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b61638 that was originally bound here
E/ActivityThread( 2253): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b61638 that was originally bound here
E/ActivityThread( 2253): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2253): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2253): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2253): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2253): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2253): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2253): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2253): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2253): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2253): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2253): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2253): 	at bks.a(SourceFile:298)
E/ActivityThread( 2253): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2253): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2253): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2253): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
E/UpdateRequestReceiver( 4683): Received malformed URL while handling Gservices.CHANGED_ACTION
I/DownloadManager( 2448): Download 187 starting
D/PMS     (  906): acquireWL(43fc29d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2448 10021 WorkSource{10016}
E/UpdateRequestReceiver( 4683): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/UpdateRequestReceiver( 4683): Received malformed URL while handling Gservices.CHANGED_ACTION
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/Process (  906): killProcessQuiet, pid=4315
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/DownloadManager( 2448): Download 188 starting
D/PMS     (  906): acquireWL(4401fdd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2448 10021 WorkSource{10016}
I/ActivityManager(  906): Killing 4315:com.htc.backup/1000 (adj 15): empty #17
W/ActivityThread( 2448): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  906): Recipient 4315
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
I/GAV2    ( 4536): Thread[GAThread,5,main]: No campaign data found.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
I/ActivityManager(  906): Resuming delayed broadcast
V/GA-SERVICE( 2253): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
D/PMS     (  906): acquireWL(43636960): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2253 10028 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2253, uid=10028, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(43655600): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2253 10028 null
D/PMS     (  906): releaseWL(43636960): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,I/SystemUpdateService( 2253): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  906): acquireWL(4343b018): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2253 10028 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1370): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  906): releaseWL(43655600): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
I/SystemUpdateService( 2253): cancelUpdate (empty URL)
,I/SystemUpdateService( 2253): active receiver: disabled
D/libc    ( 2448): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2448): [NET] getaddrinfo-,err=8
D/libc    ( 2448): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2448): [NET] getaddrinfo-, 1
,D/libc    ( 2448): [NET] getaddrinfo_proxy+
I/ActivityManager(  906): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
D/PMS     (  906): acquireWL(42dbd550): PARTIAL_WAKE_LOCK  Icing 0x1 2253 10028 null
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2253, uid=10028, userID:0
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    ( 2448): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    (  365): [NET] +++++ res_nsend xid =8413 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    ( 2448): [NET] getaddrinfo-,err=8
D/libc    (  365): [NET] NOT IN CACHE
D/libc    ( 2448): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2448): [NET] getaddrinfo-, 1
D/libc    ( 2448): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5eae +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/PMS     (  906): releaseWL(42dbd550): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/SystemUpdateService( 2253): cancelUpdate (empty URL)
,I/SystemUpdateService( 2253): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2253, uid=10028, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
,I/GCM     ( 1370): GCM config loaded
I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(4343b018): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
,D/SystemEventReceiver( 2253): Received GSERVICES_CHANGED broadcast
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2448): [NET] getaddrinfo_proxy-, success
,I/OcrUtils( 2253): Updating ocr activity enabled=false
D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2448): [NET] getaddrinfo_proxy-, success
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2253, uid=10028, userID:0
,I/GCoreUlr( 1479): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
D/PMS     (  906): acquireWL(43b3a330): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1479 10028 null
,I/GCoreUlr( 1479): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4730 uid=10031 gids={50031, 3003, 5012}
,I/DownloadManager( 2448): Ignoring Content-Length since Transfer-Encoding is also defined
I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/DownloadManager( 2448): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  906): acquireWL(43fd2320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1479 10028 null
,D/PMS     (  906): acquireWL(43ee81d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1479 10028 null
,D/PMS     (  906): releaseWL(43fd2320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null,
,D/PMS     (  906): releaseWL(43ee81d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=18 [16][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
,D/PMS     (  906): acquireWL(43b0b820): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43b0b820): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
D/PMS     (  906): acquireWL(41daf1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
,D/PMS     (  906): releaseWL(41daf1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4730, uid=10031, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(436ecea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
,D/PMS     (  906): releaseWL(436ecea8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  906): acquireWL(42e79b78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
,D/PMS     (  906): releaseWL(42e79b78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ContactAccountLoggerTas( 2895): canRun() : Opted Out
D/PMS     (  906): acquireWL(424da310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
D/PMS     (  906): releaseWL(424da310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/Search.GservicesUpdateTask( 2895): Updating Gservices keys
,D/PMS     (  906): acquireWL(41e30290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
,D/PMS     (  906): releaseWL(41e30290): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 13.607MB for 1821008-byte allocation
,I/DownloadManager( 2448): Download 187 finished with status SUCCESS
D/PMS     (  906): acquireWL(43df6fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
D/PMS     (  906): releaseWL(43df6fe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  906): releaseWL(43fc29d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/Process (  906): killProcessQuiet, pid=4279
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 4279:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/GCoreUlr( 1479): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1479): Unknown pending intent to remove.
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(43df9b18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1479 10028 null
I/ActivityManager(  906): Recipient 4279
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GCoreUlr( 1479): Unbound from all location providers
,I/ContactAccountLoggerTas( 2895): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2895): canRun() : Opted Out
,I/DownloadManager( 2448): Download 188 finished with status SUCCESS
D/PMS     (  906): releaseWL(43df9b18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  906): releaseWL(43b3a330): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,I/GCM     ( 1370): GCM config loaded
D/PMS     (  906): releaseWL(4401fdd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 15.302MB for 1821008-byte allocation
,I/ContactAccountLoggerTas( 2895): canRun() : Opted Out
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4161, uid=10160, userID:0
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,I/dalvikvm-heap( 4161): Grow heap (frag case) to 17.039MB for 1821008-byte allocation
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/googlenow
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4161, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4161, uid=10160, userID:0
,W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Search.LoginHelper( 2895): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 2895): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2895): canRun() : Opted Out
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41f577e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 10 4 12
I/ActivityManager(  906): Resuming delayed broadcast
,I/AdsMeasurementBroadcastReceiver( 2253): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2253): Unauthorized to start the main service
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
,I/DownloadManager( 2448): Download 189 starting
D/PMS     (  906): acquireWL(423616b0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2448 10021 WorkSource{10016}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2448): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=6 [31][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(425e6210): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2448 10021 WorkSource{10016}
,I/DownloadManager( 2448): Download 190 starting
D/ConnectivityService(  906): getAllNetworkInfo called by  (2448/10021)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2448): Download 189 finished with status SUCCESS
D/PMS     (  906): releaseWL(423616b0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DownloadManager( 2448): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2448/10021)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/UpdateFetcherService( 4683): Update downloaded, starting installation
I/UpdateFetcherService( 4683): Started installation
,I/ConfigUpdateInstallReceiver(  906): Not installing, new version is <= current version
,I/DownloadManager( 2448): Download 190 finished with status SUCCESS
D/PMS     (  906): releaseWL(425e6210): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/DownloadManager( 2448): Download 190 already finished; skipping
,W/ContextImpl( 4683): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4683): Update downloaded, starting installation
,I/UpdateFetcherService( 4683): Started installation
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/AutoSetting( 1465): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4333
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4333:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4333
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  906): Sleep timeout!  Sleeping now.
,D/PMS     (  906): releaseWL(4200c098): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  906): killProcessQuiet, pid=4349
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4349:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4349
,I/GAV2    ( 4161): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  906): Activity destroy timeout for ActivityRecord{420306f0 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4401cec8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/PackageSettings(  906): Skipping PackageSetting{4226fe78 com.example.hello/10356} due to missing metadata
,D/PMS     (  906): acquireWL(4319d9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=129137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4319d9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c60798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42c60798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(44079f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4246eb70: PendingIntentRecord{4246fa30 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141699, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{423ace48: PendingIntentRecord{424bb0c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141920, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(432bb760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44079f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3ea5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(4372b6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  906): releaseWL(4372b6f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1465): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1565): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1465): service - mHandler: update timezone
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1465): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1465): service - showManualTimeZoneSelector() send notification (single)
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e27d90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 6 2 11
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(4322e5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=98
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4322e5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): releaseWL(432bb760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  906): killProcessQuiet, pid=3921
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3921:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3921
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44020f28 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/AutoSetting( 1465): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4364
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4364:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4364
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(41f13ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=189136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41f13ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424ebb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424ebb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4300c9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(4300c9a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ffd810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{425e2150: PendingIntentRecord{43943ec0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229427, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4800 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{424b7270: PendingIntentRecord{424bc2f0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452523351952, Int=10800000
,D/PMS     (  906): releaseWL(43ffd810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4800/10047)
,D/Process (  906): killProcessQuiet, pid=4121
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4121:com.android.vending/u0a73 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4121
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4363e030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{41b69db8: PendingIntentRecord{43c21a58 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231439, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{4260b2c8: PendingIntentRecord{43943ec0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231729, Int=0
,D/PMS     (  906): releaseWL(4363e030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2253/10028)
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43b00990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000},
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=249136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b00990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c81708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c81708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43f2adf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=309136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f2adf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c8b228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PMS     (  906): releaseWL(42c8b228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43c882d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=369136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c882d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4345f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4345f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42cbbe18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cbbe18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1565): [EventService] reorderNotification, total:0
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/HeadsetPhoneState( 1589): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4181): Cust_ConnectToPC   : spcsc>false
D/        ( 4181): Cust_ConnectToPC   : IPT>true
,D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4181): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4181): Index of the first 1 = -1
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4181): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4181): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4402): killProcess, pid=4402
,D/Process ( 4402): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  906): Disable input method client, pid=4402
,W/InputDispatcher(  906): channel '42510c00 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42510c00 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42510c00 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4402
D/WifiService(  906): Client connection lost with reason: 4
I/WindowState(  906): WIN DEATH: Window{42510c00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  906): Process com.test.thalitest (pid 4402) has died.
I/WindowManager(  906): WINDOW DIED Window{42510c00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4282a450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=429136, Int=0
,D/PMS     (  906): releaseWL(4282a450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4260f5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4260f5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4401f8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=489137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4401f8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b27960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b27960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426e8370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4363e168: PendingIntentRecord{43c21a58 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531738, Int=300000
,D/PMS     (  906): releaseWL(426e8370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  430): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43478ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=549136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43478ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b014d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b014d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4363dc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4363dc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/PMS     (  906): acquireWL(43f6ce40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=609137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f6ce40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f08d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f08d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1246): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1246): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1246): sku_id=99
D/ContactMessageStore( 1246): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1246): start background delete task...,
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete
,D/PMS     (  906): acquireWL(43ee7f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=669136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ee7f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43e02860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e02860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bc94f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=729136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc94f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b851e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b851e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43b36d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=789136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  906): releaseWL(43b36d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43af8b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43af8b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438daa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=849136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438daa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43789148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43789148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43675590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=909137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43675590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43670948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43670948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(4366ae10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d73c68: PendingIntentRecord{423ca9e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786415, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{422bce10: PendingIntentRecord{4229f108 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452523412674, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{423b95a8: PendingIntentRecord{422ca4c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452524072306, Int=900000
,D/PMS     (  906): acquireWL(41e71e80): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2253 10028 null
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(422ef050): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2253 10028 null
,D/PMS     (  906): releaseWL(41e71e80): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2253): Aggregate from 1452523241608 (log), 1452521612623 (data)
,D/PowerUsageService( 4623): call getInstance()
D/PMS     (  906): releaseWL(4366ae10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4623): MY_DEBUG = false
W/EventLogAggregator( 2253): Unknown tag: install_package_attempt
W/EventLogAggregator( 2253): Unknown tag: snet
,W/EventLogAggregator( 2253): Unknown tag: snet_gcore
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(422ef050): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42e1bc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=969136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e1bc58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42561358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42561358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42c8ded8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4623): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{424a3200: PendingIntentRecord{43af70c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452524142855, Int=0
,D/PMS     (  906): acquireWL(43005310): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4623 1000 null
,D/PMS     (  906): releaseWL(42c8ded8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4623): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4623): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4623): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4623): SettingOnTime = 1452549600000, randomSettingOnTime = 1452548629000
,D/SmartSyncScreenOnOffTimeReceiver( 4623): SettingOffTime = 1452538800000, randomSettingOffTime = 1452540344000
,D/SmartSyncScreenOnOffTimeReceiver( 4623): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4623): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4623): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(43005310): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(4243b4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43ba60d8: PendingIntentRecord{42478110 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012205, Int=0
,D/PMS     (  906): acquireWL(4403d670): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(4403d670): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): releaseWL(4243b4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(42ffcad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(42ffcad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(43b67f28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,D/GCM     ( 1370): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/PMS     (  906): releaseWL(43b67f28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(4300ee08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(4300ee08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=23 [126][30][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(434a3270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1029137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434a3270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42629b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42629b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e62fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1089137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e62fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b344d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b344d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43453168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1149136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43453168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440cbc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440cbc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(436a40e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1209136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436a40e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4342f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4342f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43ee9c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43ee9c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f80960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1269137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f80960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43014330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43014330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44077198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44077198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4403a7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1329136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4403a7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42cba5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cba5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bfa410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1389137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bfa410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fccba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fccba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42d01458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d01458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(438d8988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1449136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438d8988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43716db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43716db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430c81c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1509136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430c81c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4322c520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4322c520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4366dc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4366dc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44046e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1569136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44046e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bef7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43bef7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(432b6b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1629137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432b6b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42efd170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42efd170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44089280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1689137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44089280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425fdfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425fdfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4322d7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4322d7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4356fbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1749136, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4356fbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f58e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f58e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440087e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(440087e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(436524a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1809137, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436524a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438d58f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438d58f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43b4aaa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43b4aaa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  906): Prepared write state in 38ms
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-11-00-48-00.bin
,D/PMS     (  906): acquireWL(43ff8858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false),
V/AlarmManager(  906): sending alarm PendingIntent{4230dbf8: PendingIntentRecord{42309f48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1869137, Int=0
,D/PMS     (  906): releaseWL(43ff8858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fb9038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fb9038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4333bee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4333bee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4852): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4852): ====startRecUseTime====
D/htc.customization.log.level( 4852):  is 
W/CustomizationLogLevel( 4852): Level value is invalid, use default level 2
D/CustomizationManager( 4852):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4852): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4852): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4852): Parsing tag category name = system
I/CustomizationCIDLoader( 4852): Parsing tag category name = application
I/CustomizationCIDLoader( 4852): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4852): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4852): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4852): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4852): Parsing tag category name = Settings
D/CustomizationManager( 4852):  Read CID file spent 0.153 (s)
D/CustomizationManager( 4852):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4852): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4852): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4852): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4852): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4852, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4536
I/ActivityManager(  906): Killing 4536:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4519
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=1396
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3868
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4451
I/ActivityManager(  906): Killing 4519:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 1396:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 3868:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4451:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1808s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Recipient 4519
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3868
D/MediaRouterService(  906): Client com.google.android.music (pid 3868): Died!
I/ActivityManager(  906): Recipient 4451
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  906): Copying FileAsset 0x690cf0c0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 1396
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4536
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{4226fe78 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1479): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(4249f6e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1479 10028 null
D/PMS     (  906): releaseWL(4249f6e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/acms    ( 1896): Unregistering com.test.thalitest
E/acms    ( 1896): Could not unregister removed application com.test.thalitest
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/PackageBroadcastService( 2253): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4866 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/Process (  906): killProcessQuiet, pid=4730
I/ActivityManager(  906): Killing 4730:com.google.android.partnersetup/u0a31 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4730
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
F/PackageManager(  906): Unable to backup user packages state file, current changes will be lost at reboot
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/SQLiteDatabase( 2253): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2253): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2253): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2253): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2253): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2253): 	at fyb.d(SourceFile:96)
E/SQLiteDatabase( 2253): 	at fyb.a(SourceFile:220)
E/SQLiteDatabase( 2253): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteDatabase( 2253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2253): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2253): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2253): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2253): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2253): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2253): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2253): 	at fyb.d(SourceFile:96)
E/SQLiteOpenHelper( 2253): 	at fyb.a(SourceFile:220)
E/SQLiteOpenHelper( 2253): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/SQLiteOpenHelper( 2253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2253): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2253): Opened metrics.db in read-only mode
D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/SQLiteLog( 2253): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
W/dalvikvm( 2253): threadid=33: thread exiting with uncaught exception (group=0x4165de30)
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452525045384.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  906): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  906): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 18 more
E/AndroidRuntime( 2253): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2253): Process: com.google.android.gms, PID: 2253
E/AndroidRuntime( 2253): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2253): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2253): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2253): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2253): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2253): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2253): 	at fyb.a(SourceFile:223)
E/AndroidRuntime( 2253): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
E/AndroidRuntime( 2253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2253): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
I/ActivityManager(  906): Delaying start of: ServiceRecord{43e67210 u0 com.google.android.gms/.wearable.service.WearableControlService}
D/Process ( 2253): killProcess, pid=2253
I/MultiDex( 4866): install
D/Process ( 2253): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/MultiDex( 4866): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/MultiDex( 4866): loading existing secondary dex files
I/MultiDex( 4866): load found 1 secondary dex files
I/MultiDex( 4866): install done
I/ProviderInstaller( 4866): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2253
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Process com.google.android.gms (pid 2253) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4887 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
I/ActivityManager(  906): Resuming delayed broadcast
E/SharedPreferencesImpl( 1211): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4899 uid=10053 gids={50053, 1023, 3003, 5012}
I/MultiDex( 4887): install
I/MultiDex( 4887): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4887): loading existing secondary dex files
I/MultiDex( 4887): load found 1 secondary dex files
I/MultiDex( 4887): install done
E/SQLiteDatabase( 4866): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4866): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4866): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4866): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4866): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4866): threadid=12: thread exiting with uncaught exception (group=0x4165de30)
I/ProviderInstaller( 4887): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/AndroidRuntime( 4866): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4866): Process: com.google.android.gms.drive, PID: 4866
E/AndroidRuntime( 4866): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4866): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4866): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4866): 	at ctn.run(SourceFile:985)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4866): killProcess, pid=4866
D/Process ( 4866): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/Process (  906): killProcessQuiet, pid=4496
I/ActivityManager(  906): Killing 4496:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Recipient 4866
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4866) has died.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  906): Recipient 4496
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b20ff0 +
I/Prism.WidgetManager( 1273): onLoadItems() +
D/PluginProvider( 4899): PluginProvider onCreate
E/SQLiteDatabase( 4899): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4899): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4899): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4899): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4899): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4899): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4899): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4899): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4899): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4899): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4899): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4899): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4899): Opened registry.db in read-only mode
D/PluginProvider( 4899): current plugin count: 19
D/HtcAppUPService( 4899): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4899): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4899): provider may killed!
W/[PluginManager]RegisterService( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4899): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4899): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4899): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4899): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4899): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4899): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4917 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=4161
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4161:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4161

```
