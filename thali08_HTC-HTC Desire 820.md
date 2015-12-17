#### Test 506502785223c58_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/CustomizationManager( 4403): ====startRecUseTime====
D/htc.customization.log.level( 4403):  is 
W/CustomizationLogLevel( 4403): Level value is invalid, use default level 2
D/CustomizationManager( 4403):  Read ACC file spent 0.066 (s)
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
D/CustomizationManager( 4403):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4403):  All configurations done spent 0.107 (s)
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
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4403
D/PMS     (  903): acquireHCC(42bd2490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42bd23a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x6799ea40 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1124854312
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bcca88
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
E/cutils-trace( 4403): Error opening trace file: No such file or directory (2)
D/PMS     (  903): acquireWL(42b33b00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4414 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4414): Copying FileAsset 0x5c741428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4414): Binding Chromium to main looper Looper (main, tid 1) {41abf188}
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
I/chromium( 4414): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4414): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(41f13890): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): acquireWL(41dcf910): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431fd5c8:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4414): 1101881232: getState(). Returning 12
D/PMS     (  903): releaseWL(41dcf910): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4414): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4414): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4414): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4414): Local Branch: 
I/Adreno-EGL( 4414): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4414): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4414):                  aa63bbd948f41d15fc72f585e
W/chromium( 4414): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4414): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4414): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4414): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4414): CordovaWebView is running on device made by: HTC
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1268
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b07640, mServedView=org.apache.cordova.engine.SystemWebView{41acd2a8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +301ms
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,W/XT9_C   ( 1203): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1203): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=4414
,D/PMS     (  903): releaseWL(42b33b00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4414): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4414): JniHelper::setJavaVM(0x41598048), pthread_self() = 1662726064
,D/JX-Cordova( 4414): jxcore cordova android initializing
,D/PMS     (  903): acquireWL(42080808): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(42080808): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(423b0910): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(423b0910): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(41e36118): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(41e36118): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(4253a3c0): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(4253a3c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.555MB for 96598-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.613MB for 144892-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.715MB for 217334-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.892MB for 325996-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.166MB for 488990-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 13.173MB for 1100216-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 14.057MB for 1650320-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 15.433MB for 2475476-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 17.468MB for 3713210-byte allocation
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(42bd2490): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42bd23a0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4414): Initializing JXcore engine
,W/jxcore-log( 4414): JXcore engine is ready
,W/jxcore-log( 4414): Starting JXcore engine
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
,W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(41fda4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
V/AlarmManager(  903): sending alarm PendingIntent{42705fa0: PendingIntentRecord{42555dc0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450312717932, Int=1800000
D/PMS     (  903): acquireWL(425c74c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2236 10028 null
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4460 uid=10077 gids={50077}
,V/AlarmManager(  903): sending alarm PendingIntent{41ad5f30: PendingIntentRecord{41ee39d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450312739927, Int=60000
,D/PMS     (  903): releaseWL(41fda4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(42015dd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(425c74c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2236): Aggregate from 1450312688833 (log), 1450310917780 (data)
,D/PMS     (  903): acquireWL(425f2ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
D/SMSBackup( 4460): SMSBackupAgentService started
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=104573, Int=0
D/SMSBackup( 4460): Checking restore status
D/SMSBackup( 4460): Restore complete
D/SMSBackup( 4460): cancelCheckAlarm
,D/SMSBackup( 4460): SMSBackupAgentService completed: completed in 0.0 seconds
,I/ActivityManager(  903): Killing 3624:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=3624
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(425f2ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(42015dd0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/ClockThread( 1113): now=1450312740060 next=59940
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3624
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,I/chromium( 4414): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4414): Skipped 137 frames!  The application may be doing too much work on its main thread.
,D/PMS     (  903): acquireWL(426ee3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=106 rxSum=104} preTxRxSum={txSum=105 rxSum=103}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19857 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19858 delay=15s
V/AlarmManager(  903): sending alarm PendingIntent{424cabd8: PendingIntentRecord{424c15a0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105169, Int=0
D/PMS     (  903): releaseWL(426ee3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(41f13890): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4414): Toggling radios to true
I/jxcore-log( 4414): 
,D/BluetoothAdapter( 4414): enable(): BT is already enabled..!
,D/WifiManager( 4414): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 913
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
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
D/WifiManager( 4414): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
,D/WifiManager( 4414): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): TDLS: Tear down peers
,I/wpa_supplicant( 1150): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4414): Radios toggled
I/jxcore-log( 4414): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4414, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4414): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4414): 
I/jxcore-log( 4414): Perf Test app loaded loaded
I/jxcore-log( 4414): 
I/Choreographer( 4414): Skipped 76 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4414): check test folder
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): found test : ./testFindPeers.js
I/jxcore-log( 4414): 
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1150): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1150): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1150): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7624bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1150):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1150): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1150): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_s,upplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1150): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  903):    returned true
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiPerfLock(  903): release()
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,I/jxcore-log( 4414): found test : ./testSendData.js
I/jxcore-log( 4414): 
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(430a3260): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19858 mDataStallAlarmIntent=PendingIntent{4248c208: PendingIntentRecord{424c15a0 android broadcastIntent}}
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): Fast associate: Old scan results
I/wpa_supplicant( 1150): wpa_supplicant_scan enter
I/wpa_supplicant( 1150): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1150): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1150): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1150): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
,D/ConnectivityService(  903): Provision feature enable=false
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
D/UsbnetStateTracker(  903): isAvailable+-
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  903): New client listening to asynchronous messages
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:5   entry:0xb7e47028  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7e476f0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7e47818  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb7e472d8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7e47108  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb7e475d8  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7e471d0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7e47410  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb7e42f88  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(425a2fe0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  903): acquireWL(4403a100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1150): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  903): acquireWL(43ff41c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  903): releaseWL(43ff41c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1364/10028)
D/PMS     (  903): releaseWL(4403a100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  903): releaseWL(425a2fe0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4414): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState,
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/PMS     (  903): acquireWL(42606d68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): releaseWL(42606d68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1420/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3911/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1894/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1997/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4483 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4483): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4483): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4483): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4483): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4483): Preparing secondary program dexes.
V/DexLibLoader( 4483): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4483): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4483): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4483): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4483): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4483): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4483): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4483): Creating class loader
,V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4483): Creating class loader
,V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4483): Creating class loader
,V/DexLibLoader( 4483): Finished creating class loader
V/DexLibLoader( 4483): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4483): Dex already copied
D/OdexVerifier( 4483): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4483): Creating class loader
,V/DexLibLoader( 4483): Finished creating class loader
,V/DexLibLoader( 4483): Verifying classes from secondary dexes.
,D/DexLibLoader( 4483): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4483): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/SensorManager(  903): mEventCount = 900
,W/dalvikvm( 4483): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4483): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1150): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1150): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1150): nl80211: Survey data missing
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1150): Sorted scan results
I/wpa_supplicant( 1150): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1150): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1150): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1150): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-69
I/wpa_supplicant( 1150): [NULL] 10:9a:dd:8e:22:d9 freq=2462 level=-91
D/wpa_supplicant( 1150): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1150): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1150): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1150): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1150): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1150): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1150): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1150): wpa_supplicant_pick_network+
I/wpa_supplicant( 1150): Selecting BSS from priority group 1
I/wpa_supplicant( 1150): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1150): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1150): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1150): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1150):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1150):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1150): Start print parameters
I/wpa_supplicant( 1150): wpa_s->wpa_state is 3
I/wpa_supplicant( 1150): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1150): isConcurrentMode() is 0
I/wpa_supplicant( 1150): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1150): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1150): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1150): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1150): wpa_s->reassociate is 1
I/wpa_supplicant( 1150): wpa_s->is_screen_on 1
I/wpa_supplicant( 1150): wpa_s->ifname wlan0
I/wpa_supplicant( 1150): End print parameters
I/wpa_supplicant( 1150): selected network = 1
D/wpa_supplicant( 1150): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb76264e8  current_ssid=0x0
D/wpa_supplicant( 1150): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1150): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1150): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1150): check if in concurrent case
,I/wpa_supplicant( 1150): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,E/FbInjectorInitializer( 4483): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1150): RSN: PMKSA cache search - network_ctx=0xb76264e8 try_opportunistic=0
D/wpa_supplicant( 1150): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1150): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1150): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1150): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1150): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1150): nl80211: Unsubscribe mgmt frames handle 0xb7625718 (mode change)
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1150): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7625718
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7625718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1150):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1150):   * freq=2412
D/wpa_supplicant( 1150):   * Auth Type 0
D/wpa_supplicant( 1150):   * WPA Versions 0x2
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1150): nl80211: Connect request send successfully
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(,):id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1150): reply (610) for get BSS: id=0
I/wpa_supplicant( 1150): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1150): freq=5220
I/wpa_supplicant( 1150): level=-47
I/wpa_supplicant( 1150): tsf=0000000108711243
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1150): ssid=NG7005g
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=1
I/wpa_supplicant( 1150): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): freq=2412
I/wpa_supplicant( 1150): level=-51
I/wpa_supplicant( 1150): tsf=0000000108711260
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1150): ssid=NG700
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=2
I/wpa_supplicant( 1150): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1150): freq=2427
I/wpa_supplicant( 1150): level=-69
I/wpa_supplicant( 1150): tsf=0000000108711263
I/wpa_supplicant( 1150): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1150): ssid=Gonzos
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=3
I/wpa_supplicant( 1150): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): freq=2412
I/wpa_supplicant( 1150): level=-52
I/wpa_supplicant( 1150): tsf=0000000108711256
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1150): ssid=01ABC
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=4
I/wpa_supplicant( 1150): bssid=10:9a:dd:8e:22:d9
I/wpa_supplicant( 1150): freq=2462
I/wpa_supplicant( 1150): level=-91
I/wpa_supplicant( 1150): tsf=0000000108711266
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1150): ssid=Apple AirPort
I/wpa_supplicant( 1150): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108711243, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 108711260, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -69, frequency: 2427, timestamp: 108711263, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 108711256, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: Apple AirPort, BSSID: 10:9a:dd:8e:22:d9, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2462, timestamp: 108711266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1150): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1150): nl80211: Connect event
D/wpa_supplicant( 1150): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1150): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1150): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1150): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1150): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1150): TDLS: Remove peers on association
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1150): EAPOL: enable timer tick
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1150): getPrivFuncNum +	
I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1150): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1150): Get randomness: len=32 entropy=6,
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED,
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  903): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..,
I/wpa_supplicant( 1150): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb76259f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1150):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...,
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1150): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1150):    broadcast key
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 11
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1150): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1150): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1150): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1150): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1150): EAPOL authentication completed successfully
I/wpa_supplicant( 1150): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,W/fb4a(:<default>):StaticBindingVerifier( 4483): Verify
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...,
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
,D/ConnectivityService(  903): mActiveDefaultNetwork: -1
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4190): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 1
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(4261da18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42337940 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42337940 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4483): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4483): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3390
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3390:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3390
,D/PMS     (  903): acquireWL(430bbc28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2236 10028 null
,D/PMS     (  903): acquireWL(431d1df0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(430bbc28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/PMS     (  903): releaseWL(431d1df0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1463): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4512 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1463/10053)
,D/AutoSetting( 1463): Util - no network available!
D/AutoSetting( 1463): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1463): service - mHandler: cancel location update
,D/AutoSetting( 1463): service -           changes count: 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1463/10053)
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4483): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4512): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4512): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4512): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4512): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  903): killProcessQuiet, pid=4241
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4527 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 4241:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4512/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4512/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4512/10078)
,I/ActivityManager(  903): Recipient 4241
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  903): Client connection lost with reason: 4
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/Process (  903): killProcessQuiet, pid=3892
I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4544 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Killing 3892:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.959MB for 84664-byte allocation
,E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 9.974MB for 28144-byte allocation
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4483): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4483): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4483): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4483): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 4544): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4483): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4483): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4483): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4483): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4483): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4483): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.040MB for 39954-byte allocation
,I/ActivityManager(  903): Recipient 3892
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.116MB for 79892-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,V/WebViewChromiumFactoryProvider( 4544): Binding Chromium to main looper Looper (main, tid 1) {41ac5318}
,I/LibraryLoader( 4544): Expected native library version number "",actual native library version number ""
,I/chromium( 4544): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4544): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4544): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(43bf4c18): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): acquireWL(4402c690): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  903): releaseWL(4402c690): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4544): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4544): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4544): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4544): Local Branch: 
I/Adreno-EGL( 4544): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4544): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4544):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4544): Starting up...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
,D/Process (  903): killProcessQuiet, pid=4023
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 10.281MB for 75760-byte allocation
I/ActivityManager(  903): Killing 4023:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42547860 u0 ReceiverList{42440ab8 4483 com.facebook.katana/10026/u0 remote:440cc618}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42547860 u0 ReceiverList{42440ab8 4483 com.facebook.katana/10026/u0 remote:440cc618}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4316f6b0 u0 ReceiverList{4316f650 4483 com.facebook.katana/10026/u0 remote:4316b778}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/PMS     (  903): acquireWL(436fdf20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): releaseWL(436fdf20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  903): Recipient 4023
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(430970c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/GCoreFlp( 1420): Unknown pending intent to remove.
D/PMS     (  903): releaseWL(430970c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4483): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1150): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1150): EAPOL: disable timer tick
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42127f48
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42127f48, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422edbb0
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42064310
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(4261da18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19860 delay=15s
,D/WifiWatchdogStateMachine(  903): WAN detection
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4190): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f0490
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1113): WifiActivity: 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 381ms
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(4352be58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4512/10078)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43599388)
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
D/PMN     (  903): wakingUp
V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=4414
I/WindowManager(  903): No lock screen! windowToken=null
D/PMN     (  903): onScreenOn
W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
D/NfcService( 1253): applyRouting -2
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41acd2a8 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  903): acquireWL(43770028): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): acquireWL(43a4b778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMS     (  903): releaseWL(43770028): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43a4b778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/MtpService( 1997): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1253): applyRouting - 0
,D/MtpService( 1997): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting -2
,D/AutoSetting( 1463): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  903): acquireWL(43b30130): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): releaseWL(43b30130): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  903): [LedInfo] has indicator attribute
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1463): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,I/ClockThread( 1113): stop update clock
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19861 delay=15s
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/TetherSettings( 4190): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4190): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4190): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4190): Cust_ConnectToPC   : spcsc>false
D/        ( 4190): Cust_ConnectToPC   : IPT>true
,D/        ( 4190): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/SmartNS_Utility( 4190): hasRemovableStorageSlot: true
I/wpa_supplicant( 1150): SET_SCREEN_ON:On
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
,I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1150): getPrivFuncNum +	
I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/SmartNS_Utility( 4190): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4190): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/PMS     (  903): releaseWL(4352be58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
,I/PSReceiver( 4190): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4190): onReceive:android.intent.action.USER_PRESENT
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/Settings( 4190): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4190):  defaultType:0
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  903): updateScreenOn: false
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4629 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  903): acquireWL(44015230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOn: 1450312746535
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOn: 1450312746535
D/PMS     (  903): releaseWL(44015230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422edbb0
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422edbb0, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42064310
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(42ad09b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2236 10028 null
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): acquireWL(4349c350): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/PMS     (  903): acquireWL(4364a5a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(42ad09b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/PMS     (  903): releaseWL(4349c350): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/CheckinService( 2236): Preparing to send checkin request
,I/EventLogService( 2236): Accumulating logs since 1450312739977
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
D/PMS     (  903): acquireWL(43736358): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19861 mDataStallAlarmIntent=PendingIntent{41c73880: PendingIntentRecord{424c15a0 android broadcastIntent}}
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): SET_SCREEN_ON:Off
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1150): getPrivFuncNum +	
I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1150): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1",
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(426474c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,I/GoogleHttpClient( 2236): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2236): Using GMS GoogleHttpClient
D/PMS     (  903): releaseWL(43736358): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/NetworkPolicy(  903): updateScreenOn: false
D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
,D/ContactMessageStore( 1241): start background delete task...
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1241): size: 0 , 0
D/PMS     (  903): releaseWL(426474c0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  903): Killing 4274:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ContactMessageStore( 1241): Background delete complete
,D/Process (  903): killProcessQuiet, pid=4274
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Recipient 4274
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2236/10028)
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2236/10028)
D/WifiService(  903): New client listening to asynchronous messages
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42064310
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42064310, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42064310, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42064310
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e687c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e687c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1463): service - mHandler: cancel location update
,D/AutoSetting( 1463): service -           changes count: 0
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(426f1c08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOff
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
D/PMS     (  903): releaseWL(426f1c08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2236): awaiting user notification for token
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41c7f3b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 9 3 12
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4653 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4653): install
,I/MultiDex( 4653): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4653): loading existing secondary dex files
,I/MultiDex( 4653): load found 1 secondary dex files
,I/MultiDex( 4653): install done
,I/ProviderInstaller( 4653): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/jxcore-log( 4414): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4414): 
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4653/10028)
,W/Settings( 4653): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  903): releaseWL(430a3260): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0,
I/acms    ( 1894): Checking Certificates
I/acms    ( 1894): Checking Developer Certificates
I/acms    ( 1894): Checking Application Certificates
I/acms    ( 1894): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4412aee8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1894/1000)
I/acms    ( 1894): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1894): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto),
I/acms    ( 1894): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1894): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1894): Updating next query delay: 75600000,
I/mlserverapp( 1894): MirrorLink is never connected, don't setup ACMS programed checks
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
I/mlserverapp( 1894): cancelACMSProgrammedChecks
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1420/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3934/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4512/10078)
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3911/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/PMS     (  903): acquireWL(43fd1730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
D/PMS     (  903): releaseWL(43fd1730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): releaseWL(4412aee8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1997/10021)
,D/PMS     (  903): acquireWL(4377f460): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2236 10028 null
,D/PMS     (  903): releaseWL(4377f460): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
,D/libc    ( 1364): [NET] getaddrinfo_proxy+
,D/PMS     (  903): acquireWL(43752f28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10028 null
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d125 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/AutoSetting( 1463): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4512): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4512): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1463): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1463): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1463/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1463/10053)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
D/AutoSetting( 1463): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1463): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 215
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1835/10178)
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  903): acquireWL(439684d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(439684d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/fb4a(:<default>):UserScope( 4483): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,I/Adreno-EGL( 4653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4653): Local Branch: 
I/Adreno-EGL( 4653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4653):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1364): Connected
D/PMS     (  903): acquireWL(4316ab60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  903): releaseWL(43752f28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  903): releaseWL(4316ab60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(43102ce8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1364): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  903): acquireWL(42468a60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(43102ce8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): releaseWL(42468a60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4653): Local Branch: 
I/Adreno-EGL( 4653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4653):                  aa63bbd948f41d15fc72f585e
,E/fb4a(:<default>):LocalFbBroadcastManager( 4483): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4483/10026)
,D/PMS     (  903): releaseWL(43bf4c18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4653): Local Branch: 
I/Adreno-EGL( 4653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4653):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2236): Sending checkin request (8847 bytes)
D/libc    ( 2236): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2236): [NET] getaddrinfo-,err=8
D/libc    ( 2236): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2236): [NET] getaddrinfo-, 1
,D/libc    ( 2236): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1bfd +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2236): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2236): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2236): [NET] getaddrinfo-,err=8
D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=11 [9][1][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  903): acquireWL(42b2ba08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(42b2ba08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2236/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2236/10028)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=11 [9][1][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2236): awaiting user notification for token
D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e9d2b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 10 3 12
,I/CheckinTask( 2236): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2236): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(4364a5a8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2236): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c8d9b0 that was originally bound here
E/ActivityThread( 2236): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c8d9b0 that was originally bound here
E/ActivityThread( 2236): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2236): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2236): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2236): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2236): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2236): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2236): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2236): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2236): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2236): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2236): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2236): 	at bks.a(SourceFile:298)
E/ActivityThread( 2236): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2236): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2236): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1364): GCM config loaded
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4304
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4304:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4304
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7ebb +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,I/GAV2    ( 4544): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(4322e338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): acquireWL(43660730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1420 10028 null
,D/PMS     (  903): releaseWL(4322e338): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(43660730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  903): killProcessQuiet, pid=4321
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4321:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4321
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(42619680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41d6be50: PendingIntentRecord{4245c3d0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=128576, Int=0
,D/PMS     (  903): acquireWL(430ad928): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42619680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42449258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(430ad928): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42449258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(430bd5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(430bd5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4230e1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{422fc0f8: PendingIntentRecord{42501940 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141276, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,V/AlarmManager(  903): sending alarm PendingIntent{42385d78: PendingIntentRecord{424d4fe0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141354, Int=0
,D/PMS     (  903): acquireWL(424f63a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(424f63a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(4309f128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(4230e1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3df0 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1463): service - has update message, not stop
,D/AutoSetting( 1463): service - mHandler: update timezone
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1516): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/DotMatrix( 1583): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1516): service - mHandler: update timezone
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1516): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1516): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f7b0f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  903): releaseWL(4309f128): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{4311d1a0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(4306ca58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4306ca58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(4402b9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4402b9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1463): service - handleMessage() stop self
,D/AutoSetting( 1463): service - handleMessage() quit looper
,D/AutoSetting( 1463): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=3934
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3934:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/AutoSetting( 1516): service - handleMessage() stop self
,I/ActivityManager(  903): Recipient 3934
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4291
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4291:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4291
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(43132df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
,D/PMS     (  903): releaseWL(43132df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43221518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43221518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42524118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{423ce0f0: PendingIntentRecord{41d7e900 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229589, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4701 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{42420360: PendingIntentRecord{42420308 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450312855989, Int=10800000
,D/PMS     (  903): releaseWL(42524118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4701/10047)
,D/Process (  903): killProcessQuiet, pid=4345
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4345:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4345
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42547f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{4366fb60: PendingIntentRecord{42be96a0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230893, Int=120000
,V/AlarmManager(  903): sending alarm PendingIntent{4408f828: PendingIntentRecord{41d7e900 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231155, Int=0
,D/PMS     (  903): releaseWL(42547f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(4404a540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PMS     (  903): releaseWL(4404a540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2236/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43bb24b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43bb24b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(42626c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=284573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42626c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43be1598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43be1598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4313ecb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4313ecb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4414): Connected to the server!
I/jxcore-log( 4414): 
,I/chromium( 4414): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4414): --- start :testFindPeers.js---
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): testFindPeers created [object Object]
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): serverPort is 8876
I/jxcore-log( 4414): 
W/dalvikvm( 4414): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4414): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4414): threadid=1: thread exiting with uncaught exception (group=0x41690e30)
E/AndroidRuntime( 4414): FATAL EXCEPTION: main
E/AndroidRuntime( 4414): Process: com.test.thalitest, PID: 4414
E/AndroidRuntime( 4414): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4414): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4414): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4414): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4414): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4414): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4414): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4414): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4414): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4414): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4414): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4414): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4414): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4414): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4414): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  903): App crashed! Process: com.test.thalitest
W/ActivityManager(  903):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  903): killProcessQuiet, pid=4363
,I/ActivityManager(  903): Killing 4363:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4414): killProcess, pid=4414
D/Process ( 4414): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
,I/ActivityManager(  903): Recipient 4363
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1203): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4414 uid 10348
,I/ActivityManager(  903): Recipient 4414
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  903): WIN DEATH: Window{42491a10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  903): Process com.test.thalitest (pid 4414) has died.
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(43bd9f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=344572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43bd9f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(4404c9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,I/BatteryService(  903): n_update end
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(4404c9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,E/PlayEventLogger( 4132): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4132): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4132): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4132): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41b1aa00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 2 9 3 12
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4132): [NET] getaddrinfo-,err=8
D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4132): [NET] getaddrinfo-, 1
,D/libc    ( 4132): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =96b8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4132): [NET] getaddrinfo_proxy-, success
,I/global  ( 4132): call createSocket() return a new socket.
D/libc    ( 4132): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(43770320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(43770320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43bf3cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=404573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43bf3cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4367f6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4367f6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4376b1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/PMS     (  903): releaseWL(4376b1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43673a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=464572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43673a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(430f3c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(430f3c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(434dc018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(434dc018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43b65678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=524573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b65678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(437f60e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43b43728: PendingIntentRecord{42be96a0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531162, Int=300000
,D/PMS     (  903): releaseWL(437f60e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(425f35f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(425f35f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4389e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(4389e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4360bd30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=584572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4360bd30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43706b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43706b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43f75420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43f75420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete,
,D/PMS     (  903): acquireWL(432b1c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=644573, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(432b1c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(435d8dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/PMS     (  903): releaseWL(435d8dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4366f138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(4366f138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42b2d188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=704572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b2d188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4260fbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(4260fbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(426f73a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(426f73a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(426f0cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=764573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(426f0cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44033998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(44033998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4376bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
,D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(4376bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43703328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=824572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43703328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(430be588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(430be588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(435ca160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(435ca160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42b9e368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=884573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b9e368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4347bff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1113): closing low battery warning: level=100
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(4347bff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(432318e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(432318e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(426f9ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  903): sending alarm PendingIntent{41d9da58: PendingIntentRecord{423fac48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784762, Int=0
V/AlarmManager(  903): sending alarm PendingIntent{42551098: PendingIntentRecord{42551018 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450313576314, Int=900000
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(426f9ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): Done.
,D/PowerUsageService( 4629): call getInstance()
,D/ConnectivityService(  903): Setting timer for 720seconds
D/PowerUsageList:PowerUsageHelper( 4629): MY_DEBUG = false
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(42637e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=944572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42637e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43101cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/PMS     (  903): releaseWL(43101cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4371c860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4371c860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43b28db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1004573, Int=0,
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b28db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44135330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42345db8: PendingIntentRecord{432c98b8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450313646653, Int=0
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(4363e8a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
,D/PMS     (  903): releaseWL(44135330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 23, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 2
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
I/FeedHostManager( 1268): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
D/SmartSyncScreenOnOffTimeReceiver( 4629): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOnTime = 1450314000000, randomSettingOnTime = 1450314000000
D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOffTime = 1450396800000, randomSettingOffTime = 1450397566000
,D/SmartSyncScreenOnOffTimeReceiver( 4629): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightMode = true
I/FeedHostManager( 1268): NightMode begin at 0, end at 7
,D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightModeTurnOffOnce = false
D/PMS     (  903): acquireWL(424faf28): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1268 10075 null
D/PMS     (  903): acquireWL(423df730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{424e4f68: PendingIntentRecord{43fc8ad0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450313646744, Int=0
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(4363e8a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4629): isWifiHotSpotEnabled = false
,I/FeedHostManager( 1268): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450313646744, BeginTime: 1450306800000, EndTime: 1450332000000
,V/AlarmManager(  903): sending alarm PendingIntent{423e8620: PendingIntentRecord{43bb0910 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1450306800000, Int=0
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  903): getProviders()=[gps, network]
,D/LocationManagerService(  903): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  903): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4629): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,I/FeedHostManager( 1268): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
,D/SmartSyncUtils( 4629): isCharging status = 5
D/PMS     (  903): releaseWL(424faf28): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  903): acquireWL(43ff53c0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1268 10075 null
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi ui setting = true
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4629): isWifiHotSpotEnabled = false
D/PMS     (  903): releaseWL(43ff53c0): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  903): releaseWL(423df730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
D/SmartSyncUtils( 4629): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi bWifiConnected = true
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4629/1000)
,D/PMS     (  903): acquireWL(437c6950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{4321aa20: PendingIntentRecord{42345b00 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012258, Int=0
,D/PMS     (  903): acquireWL(437f5f40): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(437f5f40): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  903): releaseWL(437c6950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(4372ca20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(4372ca20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): acquireWL(42ad0718): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  903): releaseWL(42ad0718): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(41dea4d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  903): releaseWL(41dea4d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=5 [200][10][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(437365b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(437365b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43590460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43590460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43415210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43415210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(436af228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(436af228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43bf5d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/PMS     (  903): releaseWL(43bf5d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430adfd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1124573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(430adfd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(434166e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(434166e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430f65e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): releaseWL(430f65e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42639ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1184573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42639ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42fe2b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42fb9a38: PendingIntentRecord{43562110 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450313826804, Int=0
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(42fe2b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi ui setting = true
D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4629): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4629): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi bCheckWifiData = false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4629/1000)
D/SmartSyncDataLinkTurnOffService( 4629): turnOffWifi bWifiConnected = true
D/LocationManagerService(  903): getProviders()=[gps, network]
D/LocationManagerService(  903): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  903): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4629): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4629): isCharging status = 5
,D/PMS     (  903): acquireWL(4367f690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(4367f690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436fe6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(436fe6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus,
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(43b1b318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1244573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b1b318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42594c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(42594c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430bd210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(430bd210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(437a4308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1304573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437a4308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43755950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43755950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4372b868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): releaseWL(4372b868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436bfbc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1364572, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{41f50588: PendingIntentRecord{43138090 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_ON_MOBILE, t=0, cnt=1, w=1450314000000, Int=86400000
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  903): sending alarm PendingIntent{4324c328: PendingIntentRecord{44007a58 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_ON_WIFI, t=0, cnt=1, w=1450314000000, Int=86400000
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(436bfbc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43418550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/PMS     (  903): releaseWL(43418550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430cb530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(430cb530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(435629d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1424573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(435629d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43ffde10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ffde10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4238fd70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(4238fd70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430d12b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1484572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(430d12b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43f785e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43f785e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(425a54f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(425a54f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(425ee8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1544572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425ee8b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43aa5420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43aa5420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43fff598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43fff598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4261a288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1604572, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4261a288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4316b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4316b4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4316fb78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(4316fb78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436404c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1664573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(436404c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43fe2e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43fe2e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(44041b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(44041b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430b2970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1724572, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(430b2970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bf75f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43bf75f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4348ef78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4348ef78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43682cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1784573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43682cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43b53dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43b53dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43dc8b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43dc8b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(43dae708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1844573, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  903): Prepared write state in 31ms
,D/PMS     (  903): releaseWL(43dae708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-16-12-12-34.bin
,D/PMS     (  903): acquireWL(435f0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/BatteryService(  903): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(435f0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(430ac5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(430ac5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42695b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
D/Process (  903): killProcessQuiet, pid=4460
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/Process (  903): killProcessQuiet, pid=4132
V/AlarmManager(  903): sending alarm PendingIntent{41b65d08: PendingIntentRecord{41d41b28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1904573, Int=0
I/ActivityManager(  903): Killing 4460:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1800s
,I/ActivityManager(  903): Killing 4132:com.android.vending/u0a73 (adj 15): empty for 1815s
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  903): killProcessQuiet, pid=4378
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4378:com.android.settings:remote/1000 (adj 15): empty for 1829s
,I/ActivityManager(  903): Recipient 4460
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): releaseWL(42695b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4132
,I/ActivityManager(  903): Recipient 4378
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=4512
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  903): killProcessQuiet, pid=1463
D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  903): Killing 4512:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/PMS     (  903): acquireWL(43465bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41d9da58: PendingIntentRecord{423fac48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1660916, Int=0
,I/ActivityManager(  903): Killing 1463:com.htc.sense.hsp/u0a53 (adj 15): empty for 1800s
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  903): killProcessQuiet, pid=3911
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 3911:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
,D/Process (  903): killProcessQuiet, pid=4190
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 4190:com.android.settings/1000 (adj 15): empty for 1801s
I/ActivityManager(  903): Recipient 4512
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  903): sending alarm PendingIntent{4234cee8: PendingIntentRecord{424d68b8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820974, Int=1800000
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
I/ActivityManager(  903): Recipient 3911
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): acquireWL(44126040): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/MediaRouterService(  903): Client com.google.android.music (pid 3911): Died!
,V/AlarmManager(  903): sending alarm PendingIntent{41c6e050: PendingIntentRecord{42345b00 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912364, Int=0
,D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Recipient 4190
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  903): sending alarm PendingIntent{42551098: PendingIntentRecord{42551018 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450314476314, Int=900000
,V/AlarmManager(  903): sending alarm PendingIntent{421b7378: PendingIntentRecord{42555dc0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450314540025, Int=1800000
,D/PMS     (  903): releaseWL(44126040): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  903): acquireWL(43a53b78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
D/PMS     (  903): releaseWL(43a53b78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  903): acquireWL(44011e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  903): releaseWL(44011e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/PMS     (  903): acquireWL(43db2df0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2236 10028 null
D/PMS     (  903): releaseWL(43465bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  903): acquireWL(437104f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2236 10028 null
I/EventLogService( 2236): Aggregate from 1450312746590 (log), 1450312739977 (data)
D/PMS     (  903): releaseWL(43db2df0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/ActivityManager(  903): Recipient 1463
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/PMS     (  903): releaseWL(437104f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
W/BatSI   (  903): Couldn't get kernel wake lock stats
E/cutils-trace( 4804): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4804): ====startRecUseTime====
D/htc.customization.log.level( 4804):  is 
W/CustomizationLogLevel( 4804): Level value is invalid, use default level 2
D/CustomizationManager( 4804):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4804): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4804): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4804): Parsing tag category name = system
I/CustomizationCIDLoader( 4804): Parsing tag category name = application
I/CustomizationCIDLoader( 4804): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4804): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4804): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4804): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4804): Parsing tag category name = Settings
D/CustomizationManager( 4804):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4804):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4804): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4804): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4804): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4804): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4804, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  903): Copying FileAsset 0x6e734d68 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  903): Skipping PackageSetting{4220cec0 com.example.hello/10356} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/dalvikvm-heap( 4168): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/acms    ( 1894): Unregistering com.test.thalitest
E/acms    ( 1894): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1420): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): acquireWL(4411c0f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1420 10028 null
I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
D/PMS     (  903): releaseWL(4411c0f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1285): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Scheme: "smsto"
E/ExternalAccountType( 1328): Unsupported attribute readOnly
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
D/PackageBroadcastService( 2236): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4818 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Delaying start of: ServiceRecord{431ff470 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4818): install
I/MultiDex( 4818): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/MultiDex( 4818): loading existing secondary dex files
I/MultiDex( 4818): load found 1 secondary dex files
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4818): install done
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4834 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2236): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2236, uid=10028, userID:0
I/ProviderInstaller( 4818): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 2236): doRemovePackageData com.test.thalitest
D/PMS     (  903): acquireWL(43781d80): PARTIAL_WAKE_LOCK  Icing 0x1 2236 10028 null
D/PMS     (  903): releaseWL(43781d80): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4834): install
I/MultiDex( 4834): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4834): loading existing secondary dex files
I/MultiDex( 4834): load found 1 secondary dex files
I/MultiDex( 4834): install done
I/ProviderInstaller( 4834): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Resuming delayed broadcast
E/SQLiteDatabase( 2236): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2236): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2236): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2236): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2236): Runtime exception while performing operation
E/ClearPendingStateOp( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2236): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2236): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2236): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2236): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2236): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2236): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2236): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2236): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2236): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2236): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2236): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2236): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2236): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2236): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1203): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/ActivityManager(  903): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4855 uid=10053 gids={50053, 1023, 3003, 5012}
E/DropBoxManagerService(  903): Can't write: system_app_wtf
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
D/Process (  903): killProcessQuiet, pid=4527
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4527:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  903): Recipient 4527
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4818): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4818): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4818): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4818): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4818): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4818): threadid=12: thread exiting with uncaught exception (group=0x41690e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
D/Process ( 4818): killProcess, pid=4818
D/Process ( 4818): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4818): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4818): Process: com.google.android.gms.drive, PID: 4818
E/AndroidRuntime( 4818): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4818): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4818): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4818): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
W/PackageManager(  903): Unable to load service info ResolveInfo{41f894f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PluginProvider( 4855): PluginProvider onCreate
E/SQLiteDatabase( 4855): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4855): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4855): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4855): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4855): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4855): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4855): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4855): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4855): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4855): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4855): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4855): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4855): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4855): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4855): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4855): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4855): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4855): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4855): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4855): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4855): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4855): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4855): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4855): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4855): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4855): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4855): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4855): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4855): Opened registry.db in read-only mode
D/PluginProvider( 4855): current plugin count: 19
D/HtcAppUPService( 4855): HtcUPDataProvider onCreate()
I/ActivityManager(  903): Recipient 4818
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4818) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/[PluginManager]RegisterService( 4855): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4855): provider may killed!
W/[PluginManager]RegisterService( 4855): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4855): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4855): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4855): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4855): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4855): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4855): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4855): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4855): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4855): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4871 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=4544
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4544:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4871, uid=10073, userID:0
I/ActivityManager(  903): Recipient 4544
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 4871): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4871/10073)
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4871/10073)
D/Finsky  ( 4871): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4871): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4871): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4871): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4871): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4871): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4871): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4871): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4871): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4871): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4871): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4871): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4871): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4871): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4871): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4871): threadid=25: thread exiting with uncaught exception (group=0x41690e30)
E/ActivityManager(  903): App crashed! Process: com.android.vending
D/Process (  903): killProcessQuiet, pid=4168
E/AndroidRuntime( 4871): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4871): Process: com.android.vending, PID: 4871
E/AndroidRuntime( 4871): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4871): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4871): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4871): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4871): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4871): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4871): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4871): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4871): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4871): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4871): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  903): Killing 4168:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4871, uid=10073, userID:0
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4871): killProcess, pid=4871
D/Process ( 4871): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2921): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4906 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Recipient 4871
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.vending (pid 4871) has died.
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
E/SQLiteLog( 2921): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2921): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63b45f50
W/dalvikvm( 2921): threadid=14: thread exiting with uncaught exception (group=0x41690e30)
I/TrimMemoryManager( 1268): [trimMemory] 5
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2921): killProcess, pid=2921
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
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2921): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  903): Recipient 4168
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2921
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2921) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/WifiService(  903): Client connection lost with reason: 4
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2921): Died!
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
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
W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
W/dalvikvm( 4906): threadid=11: thread exiting with uncaught exception (group=0x41690e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4906): FATAL EXCEPTION: Open database in background
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
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4906): killProcess, pid=4906

```
