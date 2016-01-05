#### Test 550731521dbc378_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=218 rxSum=193} preTxRxSum={txSum=142 rxSum=124}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20170 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20171 delay=15s
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(43ce9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{425dc7c8: PendingIntentRecord{425576d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103572, Int=0
D/PMS     (  907): releaseWL(43ce9578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
E/cutils-trace( 4545): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4545): ====startRecUseTime====
D/htc.customization.log.level( 4545):  is 
W/CustomizationLogLevel( 4545): Level value is invalid, use default level 2
D/CustomizationManager( 4545):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4545): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4545): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4545): Parsing tag category name = system
I/CustomizationCIDLoader( 4545): Parsing tag category name = application
I/CustomizationCIDLoader( 4545): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4545): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4545): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4545): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4545): Parsing tag category name = Settings
D/CustomizationManager( 4545):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4545):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4545): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4545): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4545): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4545): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4545
D/PMS     (  907): acquireHCC(425dc730): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(442289b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x677a8f20 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1112807024
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cb38f8
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  907): acquireWL(42399438): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4556 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4556): Copying FileAsset 0x5c6ef420 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4556): Binding Chromium to main looper Looper (main, tid 1) {41a7eaa8}
I/LibraryLoader( 4556): Expected native library version number "",actual native library version number ""
I/chromium( 4556): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4556): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440785b0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): acquireWL(44156908): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(42613330): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): releaseWL(42613330): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4556): 1101615000: getState(). Returning 12
I/Adreno-EGL( 4556): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4556): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4556): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4556): Local Branch: 
I/Adreno-EGL( 4556): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4556): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4556):                  aa63bbd948f41d15fc72f585e
W/chromium( 4556): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4556): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4556): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4556): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4556): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4556): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4556): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4556): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4556): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4556): CordovaWebView is running on device made by: HTC
,W/AwContents( 4556): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1272
,W/ResourceType( 4556): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4556): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac6648, mServedView=org.apache.cordova.engine.SystemWebView{41a8c2b0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4556): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +284ms
I/InputMethodManagerService(  907): Enable input method client, pid=4556
,D/PMS     (  907): releaseWL(42399438): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/JsMessageQueue( 4556): Set native->JS mode to OnlineEventsBridgeMode
,I/SensorManager(  907): mEventCount = 1050
,D/jxcore_app_log( 4556): JniHelper::setJavaVM(0x41555048), pthread_self() = 1662583816
,D/JX-Cordova( 4556): jxcore cordova android initializing
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4601 uid=10078 gids={50078}
,D/PMS     (  907): acquireWL(41c25628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10078}
,V/AlarmManager(  907): sending alarm PendingIntent{424fa8e0: PendingIntentRecord{424c9038 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1451989126972, Int=60000
,D/PMS     (  907): releaseWL(41c25628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4601): SMSBackupAgentService started
,D/SMSBackup( 4601): Checking restore status
D/SMSBackup( 4601): Restore complete
,D/SMSBackup( 4601): cancelCheckAlarm
,D/SMSBackup( 4601): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=4310
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
I/ActivityManager(  907): Killing 4310:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4310
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 11.625MB for 96598-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 11.706MB for 144892-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 11.821MB for 217334-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 11.998MB for 325996-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 12.272MB for 488990-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 13.279MB for 1100216-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 14.154MB for 1650320-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 15.520MB for 2475476-byte allocation
,I/dalvikvm-heap( 4556): Grow heap (frag case) to 17.549MB for 3713210-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(425dc730): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(442289b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4556): Initializing JXcore engine
,W/jxcore-log( 4556): JXcore engine is ready
,W/jxcore-log( 4556): Starting JXcore engine
,W/jxcore-log( 4556): Platform android
W/jxcore-log( 4556): 
,W/jxcore-log( 4556): Process ARCH arm
W/jxcore-log( 4556): 
,I/jxcore-log( 4556): JXcore Cordova bridge is ready!
I/jxcore-log( 4556): 
,W/jxcore-log( 4556): JXcore engine is started
,I/Choreographer( 4556): Skipped 141 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4556): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(44156908): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:267, mTXpacketCount:204, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  907): acquireWL(43c540a8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c540a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(439ac658): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(439ac658): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43530f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{434573f8: PendingIntentRecord{43be56d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451989130573, Int=0
,D/PMS     (  907): releaseWL(43530f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,I/jxcore-log( 4556): Toggling radios to true
I/jxcore-log( 4556): 
,D/BluetoothAdapter( 4556): enable(): BT is already enabled..!
,D/WifiManager( 4556): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
,W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1296
W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4556, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 8(ms)
D/WifiManager( 4556): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4556): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): TDLS: Tear down peers
I/wpa_supplicant( 1176): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4556): Radios toggled
I/jxcore-log( 4556): 
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4556): Received device characteristics:
I/jxcore-log( 4556): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4556): Bluetooth name: HTC Desire 820
I/jxcore-log( 4556): Device name: HTC-HTC Desire 820
I/jxcore-log( 4556): 
I/jxcore-log( 4556): Perf Test app loaded loaded
I/jxcore-log( 4556): 
I/jxcore-log( 4556): check test folder
I/jxcore-log( 4556): 
I/jxcore-log( 4556): found test : ./testFindPeers.js
I/jxcore-log( 4556): 
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1176): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1176): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1176): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1176): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb71b6bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1176):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1176): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1176): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1176): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    r,eturned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1176): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/jxcore-log( 4556): found test : ./testSendData.js
I/jxcore-log( 4556): 
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(440ca9d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: RECONNECT
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20171 mDataStallAlarmIntent=PendingIntent{4239f150: PendingIntentRecord{425576d8 android broadcastIntent}}
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): Fast associate: Old scan results
I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
,D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1,
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
,D/WISPrService( 3911): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,D/UsbnetStateTracker(  907): isAvailable+-
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3911): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1375): Read error: ssl=0x65fbbd30: I/O error during system call, Connection timed out
D/WISPrService( 3911): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] entry_id:4   entry:0xb7755220  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb77510f8  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7755318  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7750f58  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb77554f0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7755428  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb7754fd8  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb77550e8  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb77512a0  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,D/WISPrService( 3911): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/PMS     (  907): acquireWL(439881a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NativeCrypto( 1375): SSL shutdown failed: ssl=0x65fbbd30: I/O error during system call, Broken pipe
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(4414f1a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1375/10029)
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/BatSI   (  907): WIFI scan started for: 650a0301 uid:1000
D/PMS     (  907): releaseWL(439881a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  907):    returned false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/PMS     (  907): releaseWL(4414f1a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,I/Choreographer( 4556): Skipped 89 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4556): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 4202): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4202): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426016c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(426016c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4340/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3988/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029),
I/NetworkMonitor( 3988): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4340/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2384/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4624 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4624): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4624): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4624): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4624): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4624): Preparing secondary program dexes.
V/DexLibLoader( 4624): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4624): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4624): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4624): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4624): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4624): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4624): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4624): Dex already copied
D/OdexVerifier( 4624): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4624): Creating class loader
,V/DexLibLoader( 4624): Finished creating class loader
V/DexLibLoader( 4624): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4624): Dex already copied
D/OdexVerifier( 4624): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4624): Creating class loader
,V/DexLibLoader( 4624): Finished creating class loader
,V/DexLibLoader( 4624): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4624): Dex already copied
D/OdexVerifier( 4624): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4624): Creating class loader
,V/DexLibLoader( 4624): Finished creating class loader
V/DexLibLoader( 4624): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4624): Dex already copied
D/OdexVerifier( 4624): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4624): Creating class loader
,V/DexLibLoader( 4624): Finished creating class loader
,V/DexLibLoader( 4624): Verifying classes from secondary dexes.
,D/DexLibLoader( 4624): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4624): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4624): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1176): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1176): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1176): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1176): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1176): Start print parameters
I/wpa_supplicant( 1176): wpa_s->wpa_state is 3
I/wpa_supplicant( 1176): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1176): isConcurrentMode() is 0
I/wpa_supplicant( 1176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1176): wpa_s->reassociate is 1
I/wpa_supplicant( 1176): wpa_s->is_screen_on 1
I/wpa_supplicant( 1176): wpa_s->ifname wlan0
I/wpa_supplicant( 1176): End print parameters
I/wpa_supplicant( 1176): selected network = 2
D/wpa_supplicant( 1176): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb71b84e8  current_ssid=0x0
D/wpa_supplicant( 1176): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1176): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1176): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1176): check if in concurrent case
,I/wpa_supplicant( 1176): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1176): RSN: PMKSA cache search - network_ctx=0xb71b84e8 try_opportunistic=0
D/wpa_supplicant( 1176): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1176): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1176): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1176): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1176): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1176): nl80211: Unsubscribe mgmt frames handle 0xb71b7718 (mode change)
D/wpa_supplicant( 1176): nl80211: Subscribe to mgmt frames with non-AP handle 0xb71b7718
,D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718,
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb71b7718
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1176):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1176):   * freq=2412
D/wpa_supplicant( 1176):   * Auth Type 0
D/wpa_supplicant( 1176):   * WPA Versions 0x2
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1176): nl80211: Connect request send successfully
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-46
I/wpa_supplicant( 1176): tsf=0000000110721171
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-53
I/wpa_supplicant( 1176): tsf=0000000110721185
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000110721190
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
,I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-82
I/wpa_supplicant( 1176): tsf=0000000110721194
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 110721171, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 110721185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 110721190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 110721194, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0301 uid:1000
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4624): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1176): Wireless event: cmd=0x8b15 len=20
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1176): nl80211: Connect event
D/wpa_supplicant( 1176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1176): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1176): Add randomness: count=11 entropy=4,
I/wpa_supplicant( 1176): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1176): TDLS: Remove peers on association
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
D/Tethering(  907): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state CONNECTING,
D/wpa_supplicant( 1176): EAPOL: enable timer tick
D/wpa_supplicant( 1176): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1176): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1176): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
,E/FbInjectorInitializer( 4624): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1176): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb71b79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1176):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1176): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f47b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1176):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1176): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1176): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1176): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1176): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1176): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1176): set send_ind_to_ndc = 0
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1176): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1176): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1176): EAPOL authentication completed successfully
I/wpa_supplicant( 1176): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 3911): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3911): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 1
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP,
D/PMS     (  907): acquireWL(42bb4f88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4255f3c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4255f3c0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4624): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4624): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4624): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4340
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4340:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4340
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4651 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/AutoSetting( 1324): Util - no network available!
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
D/AutoSetting( 1324): service - mHandler: cancel location update
D/AutoSetting( 1324): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4651): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4651): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4651): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4651): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4664 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4359
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4359:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
,W/fb4a(:<default>):UserScope( 4624): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4624): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/ActivityManager(  907): Recipient 4359
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4624): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4624): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/Process (  907): killProcessQuiet, pid=4327
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4681 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4327:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4624): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4624): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4624): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4624): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4624): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4624): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4624): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4624): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4624): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4624): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4624): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/ContextImpl( 4681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4624): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4624): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4624): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4624): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4624): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4624): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4624): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4681): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4681): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 9.917MB for 39954-byte allocation
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4327
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 9.994MB for 79892-byte allocation
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 10.067MB for 84664-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4681/10151)
,V/WebViewChromiumFactoryProvider( 4681): Binding Chromium to main looper Looper (main, tid 1) {41a84218}
,I/LibraryLoader( 4681): Expected native library version number "",actual native library version number ""
,I/chromium( 4681): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4681): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(4412bdb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  907): acquireWL(42d47df0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4681): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(4412bdb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4681): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4681): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4681): Local Branch: 
I/Adreno-EGL( 4681): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4681): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4681):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 10.094MB for 28144-byte allocation
,I/NSApplication( 4681): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4681/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4681/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4174/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4174/10160)
,D/Process (  907): killProcessQuiet, pid=4381
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4381:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/ActivityManager(  907): Recipient 4381
,I/iu.Environment( 2183): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2183): num queued entries: 0
,I/iu.UploadsManager( 2183): num updated entries: 0
,I/iu.SyncManager( 2183): NEXT; no task
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43451138 u0 ReceiverList{43451018 4624 com.facebook.katana/10027/u0 remote:426bcd00}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43451138 u0 ReceiverList{43451018 4624 com.facebook.katana/10027/u0 remote:426bcd00}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c921a0 u0 ReceiverList{43c92140 4624 com.facebook.katana/10027/u0 remote:42a4d7f0}}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/wpa_supplicant( 1176): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1176): EAPOL: disable timer tick
,D/PMS     (  907): acquireWL(441b3f90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(441b3f90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4624): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4624): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425ce380 u0 com.htc.htclocationservice/.AutoSettingService}
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
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
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42bb4f88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20173 delay=15s
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/MDST    (  907): default: setTeardownRequested(true)
,D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 3911): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424057c0
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(43281a68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
,D/PMS     (  907): acquireWL(430bbce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1451989093772 min interval config: 0 actual interval: 41218
D/PMS     (  907): acquireWL(43034850): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(430bbce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checking schedule, now: 1451989134998 next: 1451989123683
,I/CheckinService( 2183): active receiver: enabled
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1451989089348
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43281a68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4756 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4756): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;,
,W/dalvikvm( 4756): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4756): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4756): install
,I/MultiDex( 4756): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4756): loading existing secondary dex files
,I/MultiDex( 4756): load found 3 secondary dex files
,I/MultiDex( 4756): install done
,W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4756): VFY: unable to resolve instance field 36
,W/dalvikvm( 4756): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4756): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4756): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/LocationInitializer( 2183): Restart initialization of location
,W/dalvikvm( 4756): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4756): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AuthorizationBluetoothService( 1375): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1375): Proximity feature is not enabled.
,W/dalvikvm( 4756): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4756): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4756): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4756): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4756): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1223): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  907): acquireWL(4245d368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4245d368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,I/WVCdm   (  373): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  373): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4756): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  373): PrepareKeyRequest: nonce=3338756969
,I/WVCdm   (  373): CdmEngine::CloseSession
,W/dalvikvm( 4556): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4556): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4556): FATAL EXCEPTION: main
E/AndroidRuntime( 4556): Process: com.test.thalitest, PID: 4556
E/AndroidRuntime( 4556): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4556): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4556): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4556): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4556): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4556): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4556): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4556): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4556): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4556): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4556): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4556): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4556): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4556): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4556): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4556): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4556): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4556): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4556): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  907): acquireWL(424e1760): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
,W/asset   (  907): Copying FileAsset 0x63a97eb0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4756/10029)
,D/WIFI_ICON( 1115): WifiActivity: 2
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/PMS     (  907): releaseWL(440ca9d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
I/NetworkMonitor( 3988): type=WIFI subType= reason=null isConnected=true
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3988/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
V/Tethering(  907): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (4024/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1585/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43c544a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
D/PMS     (  907): acquireWL(431e06c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2384/10021)
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
D/PMS     (  907): releaseWL(431e06c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(43c544a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4651): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4651): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4756): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4756): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4756):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4681/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1324): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1324): service - onStartCommand() REMOVE current location bundle
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4174/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4174/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
D/AutoSetting( 1324): service - handleMessage() setting current location null
D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1324): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(422de790): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1451989093772 min interval config: 0 actual interval: 42322
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(422de790): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2183): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/iu.UploadsManager( 2183): num queued entries: 0
,I/iu.UploadsManager( 2183): num updated entries: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,I/iu.SyncManager( 2183): NEXT; no task
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1375): [NET] getaddrinfo-,err=8
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1375): [NET] getaddrinfo-, 1
,D/libc    ( 1375): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d13d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  907): acquireWL(425de498): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 278
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1375): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{425daa88 u0 com.test.thalitest/.MainActivity t2 f}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,I/FeedHostManager( 1272): [onResume]
,I/FeedProviderManager( 1272): onResume
D/libc    ( 1375): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1375): [NET] getaddrinfo-,err=8
I/SocialFeedProvider( 1272): +onResume
,I/SocialFeedProvider( 1272): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1272): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1272/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,W/fb4a(:<default>):UserScope( 4624): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4624): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  907): releaseWL(424e1760): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4240
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 4240:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/PMS     (  907): acquireWL(43cd7360): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/PMS     (  907): releaseWL(425de498): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43cd7360): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425c5fb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
I/ActivityManager(  907): Recipient 4240
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(425c5fb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4624): Called registerBroadcastReceiver twice.
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,D/WVCdm   (  373): PrepareKeyRequest: nonce=4193236842
,V/LightsService(  907): setLight #0: color=#3e
,I/WVCdm   (  373): CdmEngine::CloseSession
,W/Settings( 4756): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4756): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4756): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4756):                  aa63bbd948f41d15fc72f585e
V/LightsService(  907): setLight #0: color=#3b
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,V/LightsService(  907): setLight #0: color=#34
I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4756): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4756): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4756):                  aa63bbd948f41d15fc72f585e
,V/LightsService(  907): setLight #0: color=#2d
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
D/PMS     (  907): releaseWL(42d47df0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/LightsService(  907): setLight #0: color=#27
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f2e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,V/LightsService(  907): setLight #0: color=#20
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 84
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
V/LightsService(  907): setLight #0: color=#19
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,V/LightsService(  907): setLight #0: color=#14
,I/CheckinTask( 2183): Sending checkin request (12197 bytes)
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=26 [15][4][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=33 [6][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2183): Checking schedule, now: 1451989137485 next: 1452512074481
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,I/CheckinService( 2183): Checking schedule, now: 1451989137508 next: 1452512074481
,I/CheckinService( 2183): active receiver: disabled
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1451989137513
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(43034850): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/GCM     ( 1375): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SensorManager(  907): mEventCount = 1200
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a621 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
,D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4681): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(43cb3a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43cb3a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1115): now=1451989140059 next=59941
,D/Process (  907): killProcessQuiet, pid=3663
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3663:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3663
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=66 [3][2][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:50, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 10.958MB for 36920-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4624/10027)
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421d26c8
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  907): pid=907, uid=1000
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421d26c8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41eee330
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42f95c58
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 11.001MB for 48100-byte allocation
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 11.018MB for 41744-byte allocation
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 312ms
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4556
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4252fd98)
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(4311d8e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(4311d8e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(4277ab80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  907): onScreenOn
I/BatteryService(  907): n_update end
D/WIFI_ICON( 1115): WifiActivity: 1
D/PMS     (  907): releaseWL(4277ab80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MtpService( 2384): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2384): [MTP][onReceive]-
D/NfcService( 1254): applyRouting - 0
,D/AutoSetting( 1324): receiver - intent: android.intent.action.USER_PRESENT
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1254): applyRouting -2
,I/dalvikvm-heap( 4624): Grow heap (frag case) to 11.032MB for 42324-byte allocation
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): acquireWL(440d02f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): releaseWL(440d02f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/TetherSettings( 3911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3911): Cust_ConnectToPC   : spcsc>false
D/        ( 3911): Cust_ConnectToPC   : IPT>true
D/        ( 3911): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3911): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3911): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/PSReceiver( 3911): onReceive:android.intent.action.USER_PRESENT
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
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
I/SmartNS_PSService( 3911): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3911):  defaultType:0
W/ContextImpl( 3911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20174 delay=15s
D/libc    ( 4624): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4624): [NET] getaddrinfo-,err=8
D/libc    ( 4624): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4624): [NET] getaddrinfo-, 1
D/libc    ( 4624): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =283a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
I/ClockThread( 1115): stop update clock
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:On
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/WIFI_ICON( 1115): WifiActivity: 2
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,V/SRS_Proc(  373): ParamSet string: screen_state=on
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
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  907): updateScreenOn: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=100 [1][1][0]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 49
D/libc    (  365): [NET]res_nsend:resplen=93
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=3
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4624): [NET] getaddrinfo_proxy-, success
I/global  ( 4624): call createSocket() return a new socket.
D/libc    ( 4624): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4624): [NET] getaddrinfo-, SUCCESS
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4816 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(4265bda0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4265bda0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43ca8288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4816): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(432a5828): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4816 1000 null
D/PMS     (  907): releaseWL(43ca8288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOn: 1451989144183
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOn: 1451989144183
D/libc    ( 4624): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4624): [NET] getaddrinfo-,err=8
D/PMS     (  907): releaseWL(432a5828): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41eee330
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41eee330, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42f95c58
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(433d4668): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cb38f8
I/SocialFeedProvider( 1272): +onPause
,I/SocialFeedProvider( 1272): -onPause
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/SmartSyncUtils( 4816): getMobilePolicyEnabled, result = true
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20174 mDataStallAlarmIntent=PendingIntent{4245fa08: PendingIntentRecord{42438d80 android broadcastIntent}}
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:Off
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1176): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/PMS     (  907): releaseWL(433d4668): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(42d48ea0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  907): releaseWL(42d48ea0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4816): isEpsOn(), nState = 0
D/SmartSyncUtils( 4816): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4816): isEpsOn(), nState = 0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=18 [16][3][0]
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f95c58
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f95c58, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f95c58, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f95c58
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@433e44b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@433e44b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1324): service - mHandler: cancel location update
,D/AutoSetting( 1324): service -           changes count: 0
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(437001d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(437001d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(436d8a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOff
D/PMS     (  907): releaseWL(436d8a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441b3f90): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4624 10027 null
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4843 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Scheme: "sms"
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4843): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4843): MmsConfig.loadMmsSettings
,W/dalvikvm( 4843): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4843): VFY: unable to resolve instance field 36
,W/dalvikvm( 4843): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4866 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4843, uid=10111, userID:0
,W/Settings( 4843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4843, uid=10111, userID:0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4843, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4843, uid=10111, userID:0
,D/MessageFrequencyProvider( 4866): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4843, uid=10111, userID:0
D/PMS     (  907): acquireWL(424e8e08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4843 10111 null
,V/GetPrviateResource( 4866): GetPrviateResource
,V/GetPrviateResource( 4866): GetPrviateResource
,D/MmsCustomizationProvider( 4866): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/PackageManager(  907): Unable to load service info ResolveInfo{42361d40 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4866): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(424f5108): PARTIAL_WAKE_LOCK  AsyncService 0x1 4174 10160 null
,I/Babel   ( 4843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4843): MmsConfig.loadFromDatabase
D/PMS     (  907): acquireWL(423ea930): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4843): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  907): releaseWL(424e8e08): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
E/Babel   ( 4843): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4843): MmsConfig.loadFromResources
E/Babel   ( 4843): canonicalizeMccMnc: invalid mccmnc nullnull
,D/Process (  907): killProcessQuiet, pid=4463
I/Babel   ( 4843): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/MessageCustFlag( 4866): sense_version=6.0
,D/BTAccessoryUtil( 4866): createReceiver
,D/BTAccessoryUtil( 4866): registerReceiver return intent = null
D/MessageCustFlag( 4866): sku_id=99
,W/SystemReader( 4866): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  907): Killing 4463:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/dalvikvm-heap( 4174): Grow heap (frag case) to 13.517MB for 1821008-byte allocation
D/Messaging( 4866): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4866): networkCode: 
,D/MessageCustFlag( 4866): sku_id=99
D/MmsConfig( 4866): SIE smsPri: null
,D/MmsConfig( 4866): networkCode: 
D/PMS     (  907): releaseWL(424f5108): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4463
D/WifiService(  907): Client connection lost with reason: 4
D/HtcTelephonyCapability( 4866): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4866): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4866): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4866): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  907): Resuming delayed broadcast
,I/dalvikvm-heap( 4174): Grow heap (frag case) to 15.210MB for 1821008-byte allocation
,D/Process (  907): killProcessQuiet, pid=4424
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4424:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  907): Recipient 4424
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(42601888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42601888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(424f1828): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(424f1828): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437bdf20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437bdf20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42d88038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42d88038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/global  ( 4624): I/O error closing connection
I/global  ( 4624): java.net.SocketException: Socket is closed
I/global  ( 4624): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4624): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4624): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4624): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4624): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4624): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4624): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4624): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4624): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4624): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4624): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4624): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4624): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4624): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4624): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4624): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4624): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4624): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4624): Removing a connection that never existed!
D/PMS     (  907): releaseWL(441b3f90): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 475 ms] updated apps [took 475 ms] 
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  907): Activity destroy timeout for ActivityRecord{425daa88 u0 com.test.thalitest/.MainActivity t2 f}
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b10bd0 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(423ea930): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b10bd0 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/Messaging( 4866): mNeedToUpdateDate2 start
,D/MmsConfig( 4866): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4866): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4866): 
D/MmsAsyncWorkHandler( 4866): HM tk = 20001
,D/ReportIndicatorCache( 4866): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4866): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a86680
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,I/Messaging( 4866): mccmnc> 
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4866): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4866): [DraftCache/1] refresh
,D/MmsConfig( 4866): networkCode: 
,D/Messaging( 4866): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4866): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4866): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4866): createReceiver
,D/MessageCustFlag( 4866): sense_version=6.0
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Jerry   ( 4866): start to preload cursor >>>>>>>
D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4866): mNeedToUpdateDate2: false
,D/Messaging( 4866): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4866): TransactionService is going to be woken up.
,V/TransactionService( 4866): 1-Creating TransactionService
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1240): sku_id=99
V/TransactionService( 4866): onStartCommand: 1
,D/MmsSystemEventReceiver( 4866): unRegisterForConnectionStateChanges
V/TransactionService( 4866): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4866): Loading previous transactions.
,D/DraftCache( 4866): [DraftCache/484] rebuildCache
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): device_type: 1
,D/Messaging( 4866): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/MmsSmsV2Provider( 1240):  phoneType = -1
D/TransactionService( 4866): Force set service start id to 1
V/TransactionService( 4866): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4866): unRegisterForConnectionStateChanges
,D/TransactionService( 4866): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4866): Destroying TransactionService
,V/TransactionService( 4866): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1240): URI_DRAFT
,D/DraftCache( 4866): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4866): [DraftCache/484] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4866): 
D/MmsAsyncWorkHandler( 4866): HM tk = 20002
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1240): sku_id=99
D/Messaging( 4866): ViewCache CreatePreload
,D/Messaging( 4866): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4866): _has_set_default_values_2=true
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
,D/MsgPreferenceUtils( 4866): def_index: 0
,D/MsgPreferenceUtils( 4866): globalIndex = 1
D/MsgPreferenceUtils( 4866): phone state: true
D/MsgPreferenceUtils( 4866): sd state: false
,D/MsgPreferenceUtils( 4866): vIndex = 0
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4488
,I/ActivityManager(  907): Killing 4488:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4488
,I/GAV4    ( 4843): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(43107a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(43107a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/Process (  907): killProcessQuiet, pid=4024
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4024:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4024
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1324): service - mHandler: update timezone
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): service - onCreate()
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1580): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1511): service - mHandler: update timezone
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1580): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e1ccf0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 8 3 11
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(432a5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4262a8d8: PendingIntentRecord{439805b0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=140007, Int=0
,D/AutoSetting( 1324): service - handleMessage() stop self
V/AlarmManager(  907): sending alarm PendingIntent{442420b8: PendingIntentRecord{4326e238 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=152223, Int=0
D/PMS     (  907): acquireWL(42d9e978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1324): service - handleMessage() quit looper
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1324): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4503
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Killing 4503:com.android.settings:remote/1000 (adj 15): empty #17
,D/PMS     (  907): acquireWL(42d42aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42d42aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42d9e978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4256a220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432a5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(4256a220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43cb79d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): acquireWL(43b35448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Recipient 4503
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(433c3a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43cb79d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43b35448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43b39a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1451989174711 tag=VacuumService
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/PMS     (  907): releaseWL(43b39a30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(437bd1c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(437bd1c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(433c3a88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(436b72d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(436b72d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426da720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(426da720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4352f308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(44053098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44053098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(440e19f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4352f308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426b5e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(426b5e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 11794 seconds from now (1451989175478)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e0be +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 239
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(440e19f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4344ef18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(4344ef18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426248c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(426248c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4256afa0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4140
,I/ActivityManager(  907): Killing 4140:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4140
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43596038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43596038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4357cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4357cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43be6208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43be6208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43cb0908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{423e34a8: PendingIntentRecord{43c0c070 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231746, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4945 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{422f4b38: PendingIntentRecord{42638910 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1451989241032, Int=10800000
,D/PMS     (  907): releaseWL(43cb0908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4945/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/Process (  907): killProcessQuiet, pid=4601
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4601:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4601
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(440aaee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440aaee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42d41dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{423e9ae0: PendingIntentRecord{43c0c070 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=242065, Int=0
,D/PMS     (  907): releaseWL(42d41dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  907): acquireWL(43106910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43106910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4324dc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4324dc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(426c7858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=297859, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426c7858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(432e1400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(432e1400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43c083d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PMS     (  907): releaseWL(43c083d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42627010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357860, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42627010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(425bee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425bee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425b8df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425b8df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4556): killProcess, pid=4556
,D/Process ( 4556): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  907): Disable input method client, pid=4556
,I/ActivityManager(  907): Recipient 4556
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.test.thalitest (pid 4556) has died.
I/WindowState(  907): WIN DEATH: Window{424bc538 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  907): channel '424bc538 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '424bc538 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '424bc538 com.test.thalitest.MainActivity (s)'
D/WifiService(  907): Client connection lost with reason: 4
I/WindowManager(  907): WINDOW DIED Window{424bc538 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PMS     (  907): acquireWL(42ce1248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=417859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42ce1248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42c01468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42c01468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42a1f758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
V/AlarmManager(  907): sending alarm PendingIntent{4249bff0: PendingIntentRecord{42500690 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=421839, Int=300000
,V/AlarmManager(  907): sending alarm PendingIntent{43b513b0: PendingIntentRecord{43a03050 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451989494704, Int=1800000
,D/PMS     (  907): acquireWL(43452d70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42a1f758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  907): acquireWL(433dcb10): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43452d70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2183): Aggregate from 1451989135029 (log), 1451987694568 (data)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(433dcb10): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44108680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=477860, Int=0
,D/PMS     (  907): releaseWL(44108680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(440d3220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440d3220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(440c7c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=537859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440c7c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(440bc018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440bc018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(440a8768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=597859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440a8768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44078ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44078ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): start background delete task...
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/PMS     (  907): acquireWL(4406f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=657859, Int=0
,D/PMS     (  907): releaseWL(4406f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cee070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43cee070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43cbc368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cbc368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43cae550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=717859, Int=0
,D/PMS     (  907): releaseWL(43cae550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43caa518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43caa518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43caa218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=777859, Int=0
,D/PMS     (  907): releaseWL(43caa218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c68a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c68a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c577e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=837859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c577e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b536b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b536b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43b38988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=897859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b38988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b26248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b26248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(439b0278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
V/AlarmManager(  907): sending alarm PendingIntent{4249bff0: PendingIntentRecord{42500690 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=721839, Int=300000
,V/AlarmManager(  907): sending alarm PendingIntent{41d0b7e8: PendingIntentRecord{4240ff78 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=799102, Int=0
,I/ActivityManager(  907): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4971 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{438d3bc0: PendingIntentRecord{43cbce10 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{41b57de8: PendingIntentRecord{4230d460 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451989962478, Int=900000
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(439b0278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): Done.
,D/PowerUsageService( 4816): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4816): MY_DEBUG = false
D/ConnectivityService(  907): Setting timer for 720seconds
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ImageRamCache( 4971): create image Cache, size: 31457280.
I/ImageRamCache( 4971): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4971): create image Cache, size: 12582912.
I/FeedSettings( 4971): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
,I/FeedSettings( 4971): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4971): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4971): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4971): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4971): loadGridSize() with Alternative
,D/libc    ( 4971): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4971): [NET] getaddrinfo-,err=8
D/libc    ( 4971): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4971): [NET] getaddrinfo-, 1
,D/libc    ( 4971): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9fda +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/libc    (  365): [NET]Querying server xid =9fda (# 1) address = 192.168.1.1 (try=2,nscount=1)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
,D/libc    (  365): [NET]res_nsend:resplen=206
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4971): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4971/10076)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4971/10076)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/Process (  907): killProcessQuiet, pid=3988
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3988:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3988
,D/MediaRouterService(  907): Client com.google.android.music (pid 3988): Died!
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(439b8ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=957860, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(439b8ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425a20f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425a20f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43439ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41fc7eb8: PendingIntentRecord{43577898 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1014285, Int=0
D/PMS     (  907): acquireWL(426c8388): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426c8388): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43439ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43272670): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1375/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
,D/PMS     (  907): releaseWL(43272670): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=8 [103][9][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42b44cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1017859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42b44cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4262e478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/SmartSyncUtils( 4816): isEpsOn(), nState = 0
V/AlarmManager(  907): sending alarm PendingIntent{4237eb78: PendingIntentRecord{42e42328 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451990044263, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4816): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4816): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/PMS     (  907): acquireWL(44075f20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4816 1000 null
,D/PMS     (  907): releaseWL(4262e478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4816): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4816): SettingOnTime = 1452060000000, randomSettingOnTime = 1452058242000
D/SmartSyncScreenOnOffTimeReceiver( 4816): SettingOffTime = 1452045600000, randomSettingOffTime = 1452048649000
D/SmartSyncScreenOnOffTimeReceiver( 4816): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4816): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4816): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(44075f20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): acquireWL(425b8c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425b8c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(440cf2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1077859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440cf2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43ace018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ace018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43cd6770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1137859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43cd6770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c61390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c61390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(433e58f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1197859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(433e58f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425bef50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425bef50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(425bf968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1257859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425bf968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4266a118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4266a118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4346c018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1317859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4346c018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42e40190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42e40190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c0faa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41cdb970: PendingIntentRecord{424761f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1353867, Int=0
,D/PMS     (  907): acquireWL(43cd2c40): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43c0faa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(434840d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43cd2c40): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(434840d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43475a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1377859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43475a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cef238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cef238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43254598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1437859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43254598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42a298a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42a298a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(438c4e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1497860, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(438c4e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(434869c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434869c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4387c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4387c260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/TetherSettings( 3911): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3911): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3911): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3911): Cust_ConnectToPC   : spcsc>false
D/        ( 3911): Cust_ConnectToPC   : IPT>true
,D/        ( 3911): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3911): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3911): Index of the first 1 = 3
W/ContextImpl( 3911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3911): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3911): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3911): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3911): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 3911): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(42a42cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1557859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a42cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4363a1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4363a1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b2d6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b2d6a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42d52c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1617859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d52c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(431110a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(431110a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44040f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44040f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(440d1d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1677860, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440d1d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43122948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43122948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43cbf6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43cbf6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43692620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1737859, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43692620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b24548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b24548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43c07f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43c07f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42d620f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1797860, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d620f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(437d8650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437d8650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(44253828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44253828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4420a620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b970a0: PendingIntentRecord{41b8f388 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1857859, Int=0
,I/ProcessStatsService(  907): Prepared write state in 40ms
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4420a620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-02-43.bin
,D/PMS     (  907): acquireWL(441c0ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(441c0ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1580): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(440bc018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41d0b7e8: PendingIntentRecord{4240ff78 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1660414, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{41f3d7b8: PendingIntentRecord{425495d0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821149, Int=1800000
V/AlarmManager(  907): sending alarm PendingIntent{4366e948: PendingIntentRecord{43022390 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1863101, Int=0
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  907): Killing 4681:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
D/Process (  907): killProcessQuiet, pid=4681
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
V/AlarmManager(  907): sending alarm PendingIntent{42d47198: PendingIntentRecord{43577898 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1914361, Int=0
D/PMS     (  907): acquireWL(4405b1b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=4664
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  907): killProcessQuiet, pid=4651
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4664:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  907): Killing 4651:com.google.android.setupwizard/u0a79 (adj 15): empty for 1800s
V/AlarmManager(  907): sending alarm PendingIntent{41b57de8: PendingIntentRecord{4230d460 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451990862478, Int=900000
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
I/ActivityManager(  907): Recipient 4681
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(4405b1b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  907): Recipient 4651
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(439afa00): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
D/PMS     (  907): releaseWL(439afa00): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(439acb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=3 [66][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/PMS     (  907): releaseWL(440bc018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  907): Couldn't get kernel wake lock stats
,TIME-OUT KILL (timeout was 1800000ms),W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
I/ActivityManager(  907): Recipient 4664
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(421c8318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
W/BatSI   (  907): Couldn't get kernel wake lock stats
I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
D/PMS     (  907): releaseWL(439acb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1375): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PhenotypeConfigurator( 1223): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/PMS     (  907): acquireWL(43b27cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1375 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1375/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024354
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024438
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024445
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026225
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026246
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360034399
D/PMS     (  907): releaseWL(43b27cd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/libc    ( 1375): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1375): [NET] getaddrinfo-,err=8
V/NativeCrypto( 1375): SSL shutdown failed: ssl=0x63ec4210: I/O error during system call, Connection timed out
V/NativeCrypto( 1375): SSL shutdown failed: ssl=0x65fce730: I/O error during system call, Connection timed out
D/libc    ( 1375): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1375): [NET] getaddrinfo-, 1
D/libc    ( 1375): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8aa1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1375): [NET] getaddrinfo_proxy-, success
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c057 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/cutils-trace( 5014): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5014): ====startRecUseTime====
D/htc.customization.log.level( 5014):  is 
W/CustomizationLogLevel( 5014): Level value is invalid, use default level 2
D/CustomizationManager( 5014):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5014): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5014): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5014): Parsing tag category name = system
I/CustomizationCIDLoader( 5014): Parsing tag category name = application
I/CustomizationCIDLoader( 5014): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5014): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5014): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5014): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5014): Parsing tag category name = Settings
D/CustomizationManager( 5014):  Read CID file spent 0.156 (s)
D/CustomizationManager( 5014):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 5014): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5014): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5014): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5014): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=5014, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  907): Copying FileAsset 0x6fba8658 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  907): Skipping PackageSetting{4214f8e0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1580): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1580): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/dalvikvm-heap( 4174): Grow heap (frag case) to 16.947MB for 1821008-byte allocation
D/PMS     (  907): acquireWL(4405f2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 4971): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4971): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  907): releaseWL(4405f2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Scheme: "sms"
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5034 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  907): acquireWL(43c0e0f0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 151 ms] updated apps [took 150 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{423d5bc0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 5034): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5034): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5034): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5034): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5034): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5034): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5034): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5034): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5034): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5034): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5034): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5034): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5034): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5034): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5034): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5034): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5034): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5034): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5034): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5034): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5034): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5034): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5034): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5034): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5034): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5034): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5034): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5034): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5034): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5034): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5034): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5034): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5034): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5034): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5034): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5034): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5034): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5034): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5034): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5034): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5034): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5034): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5034): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5034): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5034): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5034): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5034): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5034): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5034): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5034): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5034): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5034): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5034): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5034): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5034): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5034): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5034): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5034): threadid=11: thread exiting with uncaught exception (group=0x4164de30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5034): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5034): Process: com.google.android.apps.docs, PID: 5034
E/AndroidRuntime( 5034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5034): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5034): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5034): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5034): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5034): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/Process ( 5034): killProcess, pid=5034
D/Process ( 5034): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5053 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 5034
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 5034) has died.
W/ContextImpl( 5053): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5053): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5053): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5053): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5053): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5053): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5053): threadid=10: thread exiting with uncaught exception (group=0x4164de30)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5053): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5053): Process: com.android.keychain, PID: 5053
E/AndroidRuntime( 5053): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5053): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5053): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5053): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5053): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5053): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5053): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5066 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451990938418.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5053): killProcess, pid=5053
D/Process ( 5053): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 5053
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 5053) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5066): getInstance(Context context)
D/AppTag  ( 5066): getInstance(Context context)
D/AppTag  ( 5066): onCreate()
D/PMS     (  907): acquireWL(42ce1890): PARTIAL_WAKE_LOCK  AsyncService 0x1 4174 10160 null
D/PMS     (  907): releaseWL(42ce1890): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4202): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x657fbd70
E/SQLiteLog( 1375): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1375): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f8ae58
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 1375): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5caba360
W/dalvikvm( 2183): threadid=45: thread exiting with uncaught exception (group=0x4164de30)
E/DriveAsyncService( 2183): disk I/O error (code 3850)
E/DriveAsyncService( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1375): FATAL EXCEPTION: main
E/AndroidRuntime( 1375): Process: com.google.process.gapps, PID: 1375
E/AndroidRuntime( 1375): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1375): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1375): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1375): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1375): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1375): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1375): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1375): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1375): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1375): 	... 10 more
E/AndroidRuntime( 2183): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2183): Process: com.google.android.gms, PID: 2183
E/AndroidRuntime( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2183): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2183): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2183): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1375): killProcess, pid=1375
D/Process ( 1375): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5092 uid=10098 gids={50098, 3003, 5012}
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2183): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2183): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 1375
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
D/PMS     (  907): handleWLDeath(421c8318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1
I/ActivityManager(  907): Process com.google.process.gapps (pid 1375) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
E/SQLiteLog( 2183): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2183): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2183): threadid=50: thread exiting with uncaught exception (group=0x4164de30)
E/PhenotypeInitializer( 2183): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2183): killProcess, pid=2183
I/GoogleAuthUtil( 2183): Error on service connection.
I/GoogleAuthUtil( 2183): android.os.DeadObjectException
I/GoogleAuthUtil( 2183): 	at android.os.BinderProxy.transact(Native Method)
I/GoogleAuthUtil( 2183): 	at com.google.android.b.c.a(SourceFile:334)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.t.a(SourceFile:498)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.s.a(SourceFile:908)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.s.e(SourceFile:528)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.s.d(SourceFile:450)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.s.b(SourceFile:434)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.auth.q.a(SourceFile:533)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.f.b.a(SourceFile:313)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.f.b.a(SourceFile:282)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.common.analytics.f.c(SourceFile:301)
I/GoogleAuthUtil( 2183): 	at com.google.android.gms.common.analytics.CoreAnalyticsIntentService.onHandleIntent(SourceFile:33)
I/GoogleAuthUtil( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GoogleAuthUtil( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GoogleAuthUtil( 2183): 	at android.os.Looper.loop(Looper.java:157)
I/GoogleAuthUtil( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime_2_crash( 2183): crash in the same process: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime_2_crash( 2183): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime_2_crash( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime_2_crash( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityThread( 2183): Removing dead content provider:android.content.ContentProviderProxy@41c4c178
I/ActivityManager(  907): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5107 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/DeviceManagement( 5092): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5092 dbg=false s=true
I/DeviceManagement( 5092): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5092): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5092): WorkflowService: Starting workflow service
I/DeviceManagement( 5092): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ab1fc8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5092): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5092): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5092): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5092): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5121 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5092): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5092): SessionStateController: Checking invariants...
D/Documents( 5121): Loading roots for com.android.providers.downloads.documents
I/GservicesProvider( 5107): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 5107): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 5107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5107): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 5107): 	at com.google.android.gsf.gservices.GservicesProvider.,onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 5107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 5107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5107): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5107): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5107): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5107): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5107): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5107): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5107): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5107): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
E/SQLiteDatabase( 5121): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5121): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5121): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5121): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5121): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5121): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5121): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5121): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5121): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5121): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5121): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5121): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5121): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5121): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5121): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5121): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5121): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5121): threadid=1: thread exiting with uncaught exception (group=0x4164de30)
I/ActivityManager(  907): Recipient 2183
I/ActivityManager(  907): Process com.google.android.gms (pid 2183) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): handleWLDeath(43c0e0f0): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.common.analytics.CoreAnalyticsIntentService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.pseudonymous.service.PseudonymousIdService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30998ms
E/AndroidRuntime( 5107): FATAL EXCEPTION: main
E/AndroidRuntime( 5107): Process: com.google.process.gapps, PID: 5107
E/AndroidRuntime( 5107): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5107): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5397)
E/AndroidRuntime( 5107): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/AndroidRuntime( 5107): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/AndroidRuntime( 5107): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/AndroidRuntime( 5107): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/AndroidRuntime( 5107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5107): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5107): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5107): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5107): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5107): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5107): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5107): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5107): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:
```
