#### Test 54968200254eab2_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  904): acquireWL(43199958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
--------- beginning of /dev/log/main
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43199958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/CustomizationManager( 4525): ====startRecUseTime====
D/htc.customization.log.level( 4525):  is 
W/CustomizationLogLevel( 4525): Level value is invalid, use default level 2
I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4534 uid=10077 gids={50077}
D/PMS     (  904): acquireWL(43ac4ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
V/AlarmManager(  904): sending alarm PendingIntent{426a2f00: PendingIntentRecord{421a2d88 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1451954382178, Int=60000
D/PMS     (  904): releaseWL(43ac4ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/SMSBackup( 4534): SMSBackupAgentService started
D/SMSBackup( 4534): Checking restore status
D/SMSBackup( 4534): Restore complete
D/SMSBackup( 4534): cancelCheckAlarm
D/SMSBackup( 4534): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  904): killProcessQuiet, pid=3902
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/CustomizationManager( 4525):  Read ACC file spent 0.066 (s)
I/ActivityManager(  904): Killing 3902:com.google.android.music:main/u0a154 (adj 15): empty #17
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4525): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4525): Parsing tag category name = system
I/CustomizationCIDLoader( 4525): Parsing tag category name = application
I/CustomizationCIDLoader( 4525): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4525): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4525): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4525): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4525): Parsing tag category name = Settings
D/CustomizationManager( 4525):  Read CID file spent 0.116 (s)
D/CustomizationManager( 4525):  All configurations done spent 0.116 (s)
I/ActivityManager(  904): Recipient 3902
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.music (pid 3902): Died!
W/HtcNativeFlag( 4525): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4525): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4525): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4525): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4525
D/PMS     (  904): acquireHCC(445bf0f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(44658b38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6430ef78 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1140335432
D/PMS     (  904): acquireWL(437083d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@428bd0b8
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
E/cutils-trace( 4525): Error opening trace file: No such file or directory (2)
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4549 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4549): Copying FileAsset 0x5c84e428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4549): Binding Chromium to main looper Looper (main, tid 1) {420f93d8}
I/LibraryLoader( 4549): Expected native library version number "",actual native library version number ""
I/chromium( 4549): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4549): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(43705f60): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): releaseWL(43705f60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448eef80:true
D/BluetoothAdapter( 4549): 1108405776: getState(). Returning 12
D/Process (  904): killProcessQuiet, pid=4324
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): acquireWL(449461a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
I/ActivityManager(  904): Killing 4324:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4324
,I/Adreno-EGL( 4549): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4549): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4549): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4549): Local Branch: 
I/Adreno-EGL( 4549): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4549): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4549):                  aa63bbd948f41d15fc72f585e
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/chromium( 4549): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4549): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4549): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4549): CordovaWebView is running on device made by: HTC
,W/AwContents( 4549): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  904): Disable input method client, pid=1271
W/ResourceType( 4549): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4549): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@421404c0, mServedView=org.apache.cordova.engine.SystemWebView{42106128 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  904): Enable input method client, pid=4549
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4549): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +403ms
,D/PMS     (  904): releaseWL(437083d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4549): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4549): JniHelper::setJavaVM(0x41cb2010), pthread_self() = 1662462552
,D/JX-Cordova( 4549): jxcore cordova android initializing
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 11.634MB for 96598-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 11.712MB for 144892-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 11.827MB for 217334-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 11.997MB for 325996-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 12.271MB for 488990-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 13.281MB for 1100216-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 14.198MB for 1650320-byte allocation
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 15.523MB for 2475476-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(445bf0f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(44658b38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4549): Grow heap (frag case) to 17.647MB for 3713210-byte allocation
,W/jxcore-log( 4549): Initializing JXcore engine
,W/jxcore-log( 4549): JXcore engine is ready
,W/jxcore-log( 4549): Starting JXcore engine
,W/jxcore-log( 4549): Platform android
W/jxcore-log( 4549): 
,W/jxcore-log( 4549): Process ARCH arm
W/jxcore-log( 4549): 
,D/PMS     (  904): acquireWL(43da4a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=182} preTxRxSum={txSum=174 rxSum=168}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=19893 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=19894 delay=15s
V/AlarmManager(  904): sending alarm PendingIntent{446b0a00: PendingIntentRecord{42a46fc8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106794, Int=0
D/PMS     (  904): releaseWL(43da4a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4549): JXcore Cordova bridge is ready!
I/jxcore-log( 4549): 
,W/jxcore-log( 4549): JXcore engine is started
D/PMS     (  904): releaseWL(449461a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/chromium( 4549): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:241, mTXpacketCount:225, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/SensorManager(  904): mEventCount = 1200
,I/SensorManager(  904): mEventCount = 1200
,I/jxcore-log( 4549): Toggling radios to true
I/jxcore-log( 4549): 
,D/BluetoothAdapter( 4549): enable(): BT is already enabled..!
,D/WifiManager( 4549): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1270
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
,D/WifiManager( 4549): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
D/WifiManager( 4549): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): TDLS: Tear down peers
,I/wpa_supplicant( 1133): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4549): Radios toggled
I/jxcore-log( 4549): 
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4549): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4549): 
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=4549, uid=10348
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4549): Perf Test app loaded loaded
I/jxcore-log( 4549): 
I/jxcore-log( 4549): check test folder
I/jxcore-log( 4549): 
I/jxcore-log( 4549): found test : ./testFindPeers.js
I/jxcore-log( 4549): 
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1133): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1133): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1133): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/jxcore-log( 4549): found test : ./testSendData.js
I/jxcore-log( 4549): 
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,D/wpa_supplicant( 1133): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8badbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1133):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1133): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1133): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1133): nl80211: Event message available
D/wp,a_supplicant( 1133): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1133): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/Tethering(  904): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  904):    returned true
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  904): release()
,D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/Tethering(  904): interfaceStatusChanged wlan0, false
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  904): acquireWL(43ae6a10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): Fast associate: Old scan results
I/wpa_supplicant( 1133): wpa_supplicant_scan enter
I/wpa_supplicant( 1133): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1133): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1133): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1133): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19894 mDataStallAlarmIntent=PendingIntent{42b2ae18: PendingIntentRecord{42a46fc8 android broadcastIntent}}
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): Enter handleNetworkDisconnect
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
D/UsbnetStateTracker(  904): isAvailable+-
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4182): >>>>>WISPrService start isConnected = false<<<<<
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  904): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
,D/WISPrService( 4182): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): Exit handleNetworkDisconnect
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiService(  904): New client listening to asynchronous messages
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4182): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/PMS     (  904): acquireWL(42a0ad58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4182): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:6   entry:0xb8cd0310  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8cd06f0  removed 
D/libc    (  365): [NET] entry_id:10   entry:0xb8ccff10  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8ccfd90  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8cd0818  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8ccffd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8cd0248  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb8ccfe58  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8cd0128  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8cd0410  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  904): acquireWL(42692178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  904): releaseWL(42692178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1368/10028)
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  904): acquireWL(423bf548): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
,D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  904): releaseWL(42a0ad58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  904): releaseWL(423bf548): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4549): Skipped 88 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4549): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4603 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  904): NoActiveNetworkState
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(42b68e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/PMS     (  904): releaseWL(42b68e78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4398/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4398/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,I/MusicStore( 4603): Database version: 95
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4603, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 4603): Registered
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,I/MediaRouter( 4603): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (4603/10154)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2023/10021)
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4623 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4603): getSelectedRoute
,I/NetworkMonitor( 4603): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4603/10154)
,D/ACRA    ( 4623): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  904): killProcessQuiet, pid=4345
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4603, uid=10154, userID:0
,I/ActivityManager(  904): Killing 4345:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ACRA    ( 4623): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4623): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/ActivityManager(  904): Recipient 4345
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4623): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4623): Preparing secondary program dexes.
V/DexLibLoader( 4623): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4623): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4623): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4623): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4623): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4623): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4623): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
,V/DexLibLoader( 4623): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
V/DexLibLoader( 4623): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
V/DexLibLoader( 4623): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4623): Dex already copied
D/OdexVerifier( 4623): Odex verification is skipped.
,V/DexLibLoader( 4623): Creating class loader
,V/DexLibLoader( 4623): Finished creating class loader
,V/DexLibLoader( 4623): Verifying classes from secondary dexes.
,D/DexLibLoader( 4623): DexLibLoader.ensureDexLoaded took 23 ms
,I/PMS     (  904): Going to sleep due to screen timeout...
,W/dalvikvm( 4623): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@427c0348
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,W/BatSI   (  904): Couldn't get kernel wake lock stats
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/dalvikvm( 4623): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@427c0348, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42928378
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@42633190
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/dalvikvm( 4623): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4623): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/PMS     (  904): mWirelessDisplayManager is null
,D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1133): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1133): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1133): nl80211: Survey data missing
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1133): Sorted scan results
I/wpa_supplicant( 1133): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1133): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1133): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1133): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1133): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-86
I/wpa_supplicant( 1133): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1133): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1133): [NULL] fe:94:e3:11:35:3c freq=2462 level=-92
D/wpa_supplicant( 1133): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1133): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1133): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1133): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1133): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1133): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1133): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1133): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1133): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1133): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1133): wpa_supplicant_pick_network+
I/wpa_supplicant( 1133): Selecting BSS from priority group 1
I/wpa_supplicant( 1133): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1133): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1133): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1133): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1133):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1133):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1133): Start print parameters
I/wpa_supplicant( 1133): wpa_s->wpa_state is 3
I/wpa_supplicant( 1133): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1133): isConcurrentMode() is 0
I/wpa_supplicant( 1133): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1133): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1133): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1133): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1133): wpa_s->reassociate is 1
I/wpa_supplicant( 1133): wpa_s->is_screen_on 1
I/wpa_supplicant( 1133): wpa_s->ifname wlan0
I/wpa_supplicant( 1133): End print parameters
I/w,pa_supplicant( 1133): selected network = 1
D/wpa_supplicant( 1133): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8baf4e8  current_ssid=0x0
D/wpa_supplicant( 1133): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1133): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1133): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1133): check if in concurrent case
I/wpa_supplicant( 1133): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1133): RSN: PMKSA cache search - network_ctx=0xb8baf4e8 try_opportunistic=0
D/wpa_supplicant( 1133): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1133): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1133): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1133): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1133): nl80211: Unsubscribe mgmt frames handle 0xb8bae718 (mode change)
D/wpa_supplicant( 1133): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bae718
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8bae718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1133):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133):   * freq=2412
D/wpa_supplicant( 1133):   * Auth Type 0
D/wpa_supplicant( 1133):   * WPA Versions 0x2
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1133): nl80211: Connect request send successfully
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1133): reply (1045) for get BSS: id=0
I/wpa_supplicant( 1133): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1133): freq=5220
I/wpa_supplicant( 1133): level=-51
I/wpa_supplicant( 1133): tsf=0000000110742008
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=NG7005g
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=1
I/wpa_supplicant( 1133): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-47
,I/wpa_supplicant( 1133): tsf=0000000110742003
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=NG700
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=2
I/wpa_supplicant( 1133): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-80
I/wpa_supplicant( 1133): tsf=0000000110742013
I/wpa_supplicant( 1133): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1133): ssid=Gonzos
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=3
I/wpa_supplicant( 1133): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1133): freq=2462
I/wpa_supplicant( 1133): level=-89
I/wpa_supplicant( 1133): tsf=0000000110742016
I/wpa_supplicant( 1133): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1133): ssid=UPC0039325
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=4
I/wpa_supplicant( 1133): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-47
I/wpa_supplicant( 1133): tsf=0000000110741993
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1133): ssid=01ABC
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=5
I/wpa_supplicant( 1133): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1133): freq=2437
I/wpa_supplicant( 1133): level=-86
I/wpa_supplicant( 1133): tsf=0000000110742023
I/wpa_supplicant( 1133): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=UPC5999698
I/wpa_supplicant( 1133): ====,
I/wpa_supplicant( 1133): id=6
I/wpa_supplicant( 1133): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1133): freq=2437
I/wpa_supplicant( 1133): level=-87
I/wpa_supplicant( 1133): tsf=0000000110742019
I/wpa_supplicant( 1133): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1133): ssid=UPC Wi-Free
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=7
I/wpa_supplicant( 1133): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1133): freq=2462
I/wpa_supplicant( 1133): level=-92
I/wpa_supplicant( 1133): tsf=0000000110742027
I/wpa_supplicant( 1133): flags=
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (8) end of scan result ==,
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 110742008, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 110742003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 110742013, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 110742016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 110741993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 110742023, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 110742019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 7: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 110742027, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 8 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1133): nl80211: Connect event
D/wpa_supplicant( 1133): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1133): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1133): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1133): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1133): Add randomness: count=15 entropy=8
I/wpa_supplicant( 1133): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1133): TDLS: Remove peers on association
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1133): EAPOL: enable timer tick
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1133): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1133): Get randomness: len=32 entropy=9
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
I/wpa_supplicant( 1133): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8bae9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1133):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1133): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f17b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1133):    broadcast key
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 11
,I/wpa_supplicant( 1133): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1133): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1133): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1133): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1133): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1133): set send_ind_to_ndc = 0
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1133): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1133): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 1133): EAPOL authentication completed successfully
I/wpa_supplicant( 1133): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  904): This record is existed, only update it...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent,
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WISPrService( 4182): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4182): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DhcpStateMachine(  904): [StoppedState] Start DHCP
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 1
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null,
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(43c21250): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ad0a38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ad0a38 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,W/dalvikvm( 4623): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4623): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 368ms
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): OOBE c monitor 11
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=4549
,D/PMS     (  904): acquireWL(43ae5f58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43bae6a8)
W/ResourceType( 4549): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4549): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42106128 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1257): applyRouting -2
D/PMS     (  904): releaseWL(43ae5f58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  904): wakingUp
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
I/WindowManager(  904): No lock screen! windowToken=null
D/PMN     (  904): onScreenOn
D/PMS     (  904): acquireWL(445de988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/AlarmManager(  904): ACTION_SCREEN_ON
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:On
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  904): releaseWL(445de988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/MtpService( 2023): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2023): [MTP][onReceive]-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1257): applyRouting - 0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/NfcService( 1257): applyRouting -2
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): acquireWL(4340c518): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/ClockThread( 1116): stop update clock
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  904): releaseWL(4340c518): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/NetworkPolicy(  904): updateScreenOn: false
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,E/FbInjectorInitializer( 4623): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): acquireWL(445f96f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
,D/PMS     (  904): releaseWL(445f96f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1843): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1843): onScreenOn: 1451954389541
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1843): onScreenOn: 1451954389541
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42928378
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42928378, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@42633190
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(439f3f78): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19895 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:Off
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1133): get_ip_address source addr = 02000000
I/wpa_supplicant( 1133): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904):    returned true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
D/PMS     (  904): releaseWL(439f3f78): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  904): acquireWL(4468b678): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4468b678): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/ContactMessageStore( 1246): start background delete task...
,D/NetworkPolicy(  904): updateScreenOn: false
D/ContactMessageStore( 1246): size: 0 , 0
D/ContactMessageStore( 1246): Background delete complete
,W/fb4a(:<default>):StaticBindingVerifier( 4623): Verify
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): acquireWL(439f42d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1843): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1843): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1843): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1843): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1843): onScreenOff
D/PMS     (  904): releaseWL(439f42d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4623): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4623): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=4005
,I/ActivityManager(  904): Killing 4005:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  904): releaseWL(43c21250): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -45 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/PMS     (  904): acquireWL(446f2b08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): gateway: /192.168.1.1
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1133): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
,D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -45, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/PMS     (  904): acquireWL(43aa8ea0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
D/PMS     (  904): releaseWL(446f2b08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  904): WAN detection
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a24560
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/WISPrService( 4182): >>>>>WISPrService start isConnected = true<<<<<
,D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
W/ActivityManager(  904): Failed to clear dns cache for: com.google.android.gm
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  904): acquireWL(431af258): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
I/ActivityManager(  904): Recipient 4005
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/PMS     (  904): acquireWL(43de8108): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bcbf +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4623): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  904): releaseWL(43aa8ea0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/PMS     (  904): releaseWL(431af258): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 292
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 1404): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
,D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/AutoSetting( 1404): service - onCreate()
,D/AutoSetting( 1404): service - AddressCache: using context: com.htc.Weather
I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4698 uid=10078 gids={50078, 3003, 5012}
,D/LocationManagerService(  904): request 42bb2810 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1404): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1404): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1404): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
,D/MobileConnectivityChangeReceiver( 4698): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4698): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4698): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4698): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4623): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4623): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4623): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4623): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4623): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4623): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4623): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4623): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4623): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4623): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4623): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4623): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4714 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4698/10078)
D/PMS     (  904): acquireWL(43def400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4698/10078)
D/PMS     (  904): releaseWL(43def400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4698/10078)
D/PMS     (  904): acquireWL(4468bd28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,D/PMS     (  904): acquireWL(436c30e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(4468bd28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.912MB for 39954-byte allocation
D/PMS     (  904): releaseWL(436c30e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 9.989MB for 79892-byte allocation
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4729 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4257
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4257:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4257
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 10.062MB for 84664-byte allocation
,D/wpa_supplicant( 1133): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1133): EAPOL: disable timer tick
,D/GCM     ( 1368): Connected
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4729): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/PMS     (  904): acquireWL(43a9e020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
,D/PMS     (  904): releaseWL(43de8108): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4729): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4729): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4729): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  904): releaseWL(43a9e020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(4465e700): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4729): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1368): Message class mpf
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  904): releaseWL(4465e700): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(445f2378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  904): releaseWL(445f2378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c223f0 u0 ReceiverList{42c222d0 4623 com.facebook.katana/10026/u0 remote:44666328}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c223f0 u0 ReceiverList{42c222d0 4623 com.facebook.katana/10026/u0 remote:44666328}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ade140 u0 ReceiverList{43ade0e0 4623 com.facebook.katana/10026/u0 remote:43cb0a80}}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [8][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4729/10151)
,V/WebViewChromiumFactoryProvider( 4729): Binding Chromium to main looper Looper (main, tid 1) {420f1290}
,I/LibraryLoader( 4729): Expected native library version number "",actual native library version number ""
I/chromium( 4729): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4729): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(44718238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,E/AudioManagerAndroid( 4729): BLUETOOTH permission is missing!
D/PMS     (  904): acquireWL(446f8650): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): releaseWL(44718238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  904): releaseWL(446f8650): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  904): acquireWL(446c1e28): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,I/Adreno-EGL( 4729): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4729): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4729): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4729): Local Branch: 
I/Adreno-EGL( 4729): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4729): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4729):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4729): Starting up...
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4729/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4729/10151)
,D/GCoreFlp( 1430): Unknown pending intent to remove.
D/PMS     (  904): acquireWL(446a6250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/PMS     (  904): releaseWL(446a6250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
,D/Process (  904): killProcessQuiet, pid=4398
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4398:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4772 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4398
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4772): isEpsOn(), nState = 0,
D/PMS     (  904): acquireWL(440c2090): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4772 1000 null
,D/PMS     (  904): releaseWL(440c2090): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4772): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1404): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  904): killProcessQuiet, pid=4421
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4421:com.htc.backup/1000 (adj 15): empty #17
,D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  904): Recipient 4421
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 4182): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4182): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4182): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4182): Cust_ConnectToPC   : spcsc>false
,D/        ( 4182): Cust_ConnectToPC   : IPT>true
,D/        ( 4182): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4182): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4182): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4182): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4182): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4182): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4182):  defaultType:0
W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4772): isEpsOn(), nState = 0
D/SmartSyncUtils( 4772): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4772): isEpsOn(), nState = 0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiService(  904): New client listening to asynchronous messages
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42633190
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42633190, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42633190, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42633190
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420f40d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@420f40d0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  904): releaseWL(43ae6a10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  904): NoActiveNetworkState
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1430/10028)
V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): Found interface wlan0
D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1921): Checking Certificates
I/acms    ( 1921): Checking Developer Certificates
I/acms    ( 1921): Checking Application Certificates
I/acms    ( 1921): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1921): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1921): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1921): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1921): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1921): Updating next query delay: 75600000
I/mlserverapp( 1921): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1921): cancelACMSProgrammedChecks
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(4291ef90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4603/10154)
,I/NetworkMonitor( 4603): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3924/10051)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(4339b318): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): releaseWL(4339b318): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/PMS     (  904): releaseWL(4291ef90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4698/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2023/10021)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): acquireWL(42937080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(42b4f1d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(42937080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  904): releaseWL(42b4f1d8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/AutoSetting( 1404): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4698): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4698): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1404): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4729/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
D/AutoSetting( 1404): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1404): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4160/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1884/10178)
D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4160): Grow heap (frag case) to 13.619MB for 1821008-byte allocation
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4549): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4549): threadid=1: thread exiting with uncaught exception (group=0x41cc3e30)
,E/AndroidRuntime( 4549): FATAL EXCEPTION: main
E/AndroidRuntime( 4549): Process: com.test.thalitest, PID: 4549
E/AndroidRuntime( 4549): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4549): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4549): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4549): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4549): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4549): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4549): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4549): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4549): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4549): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4549): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4549): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4549): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4549): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4549): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4549): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4549): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  904): App crashed! Process: com.test.thalitest
W/ActivityManager(  904):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  904): Killing 4438:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=4438
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  904): Recipient 4438
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4549): killProcess, pid=4549
,D/Process ( 4549): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 4549 uid 10348
,I/ActivityManager(  904): Recipient 4549
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  904): WIN DEATH: Window{42284a28 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  904): Client connection lost with reason: 4
,I/ActivityManager(  904): Process com.test.thalitest (pid 4549) has died.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4623): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4623): Called registerBroadcastReceiver twice.
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cb6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4623/10026)
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  904): acquireWL(4336e6b8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4603 10154 null
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4603): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4603, uid=10154, userID:0
,I/MusicLeanback( 4603): Conditions not met for autocaching.
,I/MusicLeanback( 4603): Stop autocaching.
D/PMS     (  904): releaseWL(4336e6b8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  904): releaseWL(446c1e28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,I/GAV2    ( 4729): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(43b31f20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  904): acquireWL(4459bdf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  904): releaseWL(43b31f20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  904): releaseWL(4459bdf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  904): killProcessQuiet, pid=3924
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3924:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3924
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(446e7228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(446e7228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1404): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1404): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1404): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43c70a60 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(429bb518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429bb518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(437168d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42b50068: PendingIntentRecord{42acdf60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141293, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42af5560: PendingIntentRecord{43d36c68 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451954408261, Int=563223000
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
,D/PMS     (  904): acquireWL(43d01988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  904): acquireWL(43d91780): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(43d01988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  904): releaseWL(437168d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(438a3f00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(43d91780): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2229): Preparing to send checkin request
,I/EventLogService( 2229): Accumulating logs since 1451954375952
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,I/GoogleHttpClient( 2229): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2229): Using GMS GoogleHttpClient
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2229/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2229/10028)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=7 [13][1][0]
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1592): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2229): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{42245fc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 5 22 9 12
,D/AutoSetting( 1404): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1592): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1592): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{421369e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 5 2 11
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4500/10028)
,I/Adreno-EGL( 4500): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4500): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4500): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4500): Local Branch: 
I/Adreno-EGL( 4500): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4500): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4500):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4500): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4500): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4500): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4500): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4500): Local Branch: 
I/Adreno-EGL( 4500): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4500): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4500):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4500): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4500): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4500): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4500): Local Branch: 
I/Adreno-EGL( 4500): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4500): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4500):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2229): Sending checkin request (8966 bytes)
D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2229): [NET] getaddrinfo-,err=8
D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2229): [NET] getaddrinfo-, 1
,D/libc    ( 2229): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f736 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 239
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2229): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-,err=8
,D/AutoSetting( 1404): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/DotMatrix( 1592): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix,
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1592): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{421838f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 1 7 2 11
,D/AutoSetting( 1404): service - handleMessage() stop self
,D/AutoSetting( 1404): service - handleMessage() quit looper
,D/AutoSetting( 1404): service - onDestroy() END
,D/PMS     (  904): acquireWL(44641ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  904): releaseWL(44641ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2229/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=11 [18][2][0]
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2229/10028)
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1592): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2229): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{424d3890 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 9 3 12
,I/CheckinTask( 2229): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2229): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  904): releaseWL(438a3f00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/GCM     ( 1368): GCM config loaded
E/ActivityThread( 2229): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@421f1f98 that was originally bound here
E/ActivityThread( 2229): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@421f1f98 that was originally bound here
E/ActivityThread( 2229): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2229): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2229): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2229): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2229): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2229): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2229): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2229): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2229): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2229): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2229): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2229): 	at bks.a(SourceFile:298)
E/ActivityThread( 2229): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2229): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2229): 	at java.lang.Thread.run(Thread.java:864)
,D/PMS     (  904): acquireWL(43890990): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(43890990): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42b93300): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(42b93300): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4468e1a8): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  904): releaseWL(4468e1a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{44645208 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43c76f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c76f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
D/Process (  904): killProcessQuiet, pid=4456
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 4456:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4456
,D/PMS     (  904): acquireWL(445e4d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{42e1bbc0: PendingIntentRecord{432313b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175654, Int=0
,D/PMS     (  904): releaseWL(445e4d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1246): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(440d72f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(440d72f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4468c190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4468c190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43f26178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f26178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(429ec160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(429ec160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(445a5bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(445a5bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(44681a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44681a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4837 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  904): acquireWL(43b64770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10047}
,V/AlarmManager(  904): sending alarm PendingIntent{4221d988: PendingIntentRecord{42206500 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1451954498654, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{44a5adc8: PendingIntentRecord{43d9dcd8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1451954637015, Int=0
,D/PMS     (  904): releaseWL(43b64770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4837/10047),
,W/Uploader( 2229): No account for auth token provided
,D/Process (  904): killProcessQuiet, pid=4472
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4472:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4472
,D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2229): [NET] getaddrinfo-,err=8
D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2229): [NET] getaddrinfo-, 1
,D/libc    ( 2229): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1e67 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 42
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2229): [NET] getaddrinfo_proxy-, success
I/global  ( 2229): call createSocket() return a new socket.
D/libc    ( 2229): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/PMS     (  904): acquireWL(4488cd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=361659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4488cd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1592): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{421369e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4122): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4122): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4122): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4122): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4122): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4122): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4122): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4122): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 19 6 12
,D/libc    ( 4122): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4122): [NET] getaddrinfo-,err=8
D/libc    ( 4122): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4122): [NET] getaddrinfo-, 1
,D/libc    ( 4122): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fc72 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4122): [NET] getaddrinfo_proxy-, success
I/global  ( 4122): call createSocket() return a new socket.
D/libc    ( 4122): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4122): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4122): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4122): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(44143460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(44143460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43b5bdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43b5bdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43b3cca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=421659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b3cca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43af4d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43af4d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43af2b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(43af2b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43aa2908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=481660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43aa2908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43a7dfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43a7dfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(435002f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(435002f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b4af50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=541660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b4af50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4296b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4296b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42601be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=601659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42601be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42354058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42354058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1246): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1246): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1246): sku_id=99
,D/ContactMessageStore( 1246): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1246): start background delete task...
D/ContactMessageStore( 1246): size: 0 , 0
,D/ContactMessageStore( 1246): Background delete complete,
,D/PMS     (  904): acquireWL(42ac06c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=661660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ac06c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42931588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42931588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  904): killProcessQuiet, pid=4385
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4385:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4385
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(423cd070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=721660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(423cd070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42a91920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42a91920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43703638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=781659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43703638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42b501c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b501c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42a97168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  904): releaseWL(42a97168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4335d548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=841659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4335d548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42adf128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(42adf128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42abb828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42abb828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(426e5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=901660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426e5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44229a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(44229a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42902060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42902060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42b281b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=961660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b281b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43af4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43af4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(42b06c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423f2900: PendingIntentRecord{42a2ed18 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785940, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{445c7710: PendingIntentRecord{42aceb20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011909, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{42c3b5d0: PendingIntentRecord{42c4eda0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451955219063, Int=900000
,D/PMS     (  904): acquireWL(42b3fdb0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1368 10028 null
V/AlarmManager(  904): sending alarm PendingIntent{43b42220: PendingIntentRecord{42b8cc10 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451955282516, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{433e1a58: PendingIntentRecord{42a69be0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451955290750, Int=0
,D/PMS     (  904): releaseWL(42b3fdb0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): acquireWL(42b62e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  904): releaseWL(42b62e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): acquireWL(4293ce18): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2229 10028 null
,D/PMS     (  904): acquireWL(43d71800): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2229 10028 null
,D/PowerUsageService( 4772): call getInstance()
,D/SmartSyncUtils( 4772): isEpsOn(), nState = 0
,I/EventLogService( 2229): Aggregate from 1451954419678 (log), 1451953482465 (data)
D/PMS     (  904): releaseWL(4293ce18): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
D/PMS     (  904): acquireWL(43399d70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4772 1000 null
,D/PowerUsageList:PowerUsageHelper( 4772): MY_DEBUG = false,
,D/SmartSyncScreenOnOffTimeReceiver( 4772): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4772): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 1, nEnd = 2, bNormalRange = true
D/PMS     (  904): releaseWL(42b06c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): acquireWL(42b03820): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/GCM     ( 1368): Message class mow
D/PMS     (  904): releaseWL(43d71800): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1368/10028)
,D/PMS     (  904): releaseWL(42b03820): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): acquireWL(42bbeb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  904): releaseWL(42bbeb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4772): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 2
,D/SmartSyncScreenOnOffTimeReceiver( 4772): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4772): SettingOnTime = 1451955600000, randomSettingOnTime = 1451955600000
D/SmartSyncScreenOnOffTimeReceiver( 4772): SettingOffTime = 1452038400000, randomSettingOffTime = 1452038818000
,I/FeedHostManager( 1271): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,I/FeedHostManager( 1271): NightMode begin at 0, end at 7
W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
D/PMS     (  904): acquireWL(43199198): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1271 10075 null
,D/SmartSyncScreenOnOffTimeReceiver( 4772): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4772): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4772): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1271): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1451955290940, BeginTime: 1451948400000, EndTime: 1451973600000
D/PMS     (  904): acquireWL(43e3bf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{42bbb3c8: PendingIntentRecord{42a6ab00 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1451955290952, Int=0
D/PMS     (  904): releaseWL(43399d70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
V/AlarmManager(  904): sending alarm PendingIntent{4386ec68: PendingIntentRecord{43b09ac0 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1451948400000, Int=0
D/PMS     (  904): releaseWL(43199198): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/SmartSyncUtils( 4772): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  904): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4772): isWifiHotSpotEnabled = false
,I/FeedHostManager( 1271): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffMobile bCheckMobileData = false
D/PMS     (  904): acquireWL(42c05160): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1271 10075 null
,D/LocationManagerService(  904): getProviders()=[gps, network]
D/LocationManagerService(  904): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  904): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/PMS     (  904): releaseWL(42c05160): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  904): releaseWL(43e3bf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
D/SmartSyncDataLinkTurnOffService( 4772): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4772): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi ui setting = true
D/WifiStateMachine(  904): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4772): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4772): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi bWifiConnected = true
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4772/1000)
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=11 [109][13][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(4435ddb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4435ddb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44128d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1021660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44128d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43cbf268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43cbf268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4182): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4182): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4182): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4182): Cust_ConnectToPC   : spcsc>false
D/        ( 4182): Cust_ConnectToPC   : IPT>true
,D/        ( 4182): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4182): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4182): Index of the first 1 = 3
W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/ContextImpl( 4182): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4182): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4182): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4182): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4182): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4182): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43490f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43490f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42ec4850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1081659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42ec4850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44694c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44694c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4324e418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4324e418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44945fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1141660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44945fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44944d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44944d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44678600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44678600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4465dfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{44674dc0: PendingIntentRecord{42a69f08 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1451955471013, Int=0
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(4465dfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi ui setting = true
,D/WifiStateMachine(  904): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4772): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4772): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4772): turnOffWifi bWifiConnected = true
,D/LocationManagerService(  904): getProviders()=[gps, network]
D/LocationManagerService(  904): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  904): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4772/1000)
D/SmartSyncDataLinkTurnOffService( 4772): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4772): isCharging status = 5
,D/PMS     (  904): acquireWL(446115b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1201659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(446115b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(445a5a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(445a5a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4408f9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4408f9f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(44079090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1261659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44079090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43ea1580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43ea1580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43af4500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43af4500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43af17d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{43b4f9f8: PendingIntentRecord{42a6a578 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_ON_WIFI, t=0, cnt=1, w=1451955600000, Int=86400000
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1321660, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{439cd258: PendingIntentRecord{42a6a228 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_ON_MOBILE, t=0, cnt=1, w=1451955600000, Int=86400000
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(43af17d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43aeee70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4265a9f0: PendingIntentRecord{42b22dc8 android broadcastIntent}}, i=com.htc.intent.action.UBLS_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1322136, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42af4610: PendingIntentRecord{431259d0 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1451955600359, Int=0
,I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4886 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  904): acquireWL(43869778): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 904 1000 null
,D/PMS     (  904): releaseWL(43869778): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,D/PMS     (  904): acquireWL(429dedb8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 904 1000 null
,D/PMS     (  904): releaseWL(429dedb8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.htc.server.ulog.EventLogStore.upload:130 com.htc.server.ulog.EventLogStore.onAlarmArrival:220 com.htc.server.ulog.AlarmScheduler$SchedulerBase$CallbackRunnable.run:155 android.os.Handler.handleCallback:733 
,D/PMS     (  904): releaseWL(43aeee70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10070}
,I/ActivityManager(  904): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.ReportAgentReceiver: pid=4900 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/MyReportAgent( 4900): ReportAgentReceiver [onReceive] com.htc.intent.action.USER_PROFILING
,D/MyReportAgent( 4900): com.htc.intent.action.USER_PROFILING
,D/Process (  904): killProcessQuiet, pid=4209
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  904): Killing 4209:com.google.android.configupdater/u0a16 (adj 15): empty #17
,D/MyReportAgent( 4900): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@421026d8
,D/MyReportAgent( 4900): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.intent.action.USER_PROFILING flg=0x10 cmp=com.htc.reportagent/.ReportService (has extras) }, this = com.htc.reportagent.ReportService@421026d8
,D/MyReportAgent( 4900): ReportServiceHandler.onHandleIntent() intent is com.htc.intent.action.USER_PROFILING
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4209
,D/UPolicy ( 4900): IUserBehaviorLoggingService reference is gotten !
,D/MyReportAgent( 4900): ReportUploader [onUpload] tag: HTC_ULOGDATA, time: 1451955600534 
,D/LocationManagerService(  904): getProviders()=[]
,D/LocationManagerService(  904): getProviders()=[passive]
,D/LocationManagerService(  904): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  904): getProviders()=[]
D/LocationManagerService(  904): getProviders()=[passive]
,D/LocationManagerService(  904): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/HandsetLogCreator( 4900): envelope SN: 130
,D/MyReportAgent( 4900): ReportUploader file size: 1509
,V/MyReportAgent( 4900): Utils getType(): 1, getSubtype: 0
,D/MyReportAgent( 4900): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.reportagent (4900/10065)
,D/Wakelock4Data( 4900): logPomeloSender_133.1KB to transmit,reason=send log to server.
V/MyReportAgent( 4900): Utils getType(): 1, getSubtype: 0
D/PMS     (  904): acquireWL(42325810): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 4900 10065 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.reportagent (4900/10065)
D/MyReportAgent( 4900): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/MyReportAgent( 4900): ReportUploader Uploaded file size: 1509
D/Pomelo  ( 4900): LogLib params context = android.app.Application@420fd0c8	isDebug = false	isEngineerROM = false
,D/PomeloConfig( 4900): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4900): LogLibStore version is 1.3
,D/PomeloConfig( 4900): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
,D/PomeloConfig( 4900): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
,D/PomeloConfig( 4900): loadFromPreference(), RefreshInterval = 604800
,D/Pomelo  ( 4900): sendLogEnvelope envelope valid
,D/Pomelo  ( 4900): inBytes=[1509]
,D/Pomelo  ( 4900): outBytes.length=[765]
,D/libc    ( 4900): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4900): [NET] getaddrinfo-,err=8
D/libc    ( 4900): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4900): [NET] getaddrinfo-, 1
,D/libc    ( 4900): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d7d0 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 3581
D/libc    (  365): [NET]res_nsend:resplen=184
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4900): [NET] getaddrinfo_proxy-, success
I/global  ( 4900): call createSocket() return a new socket.
D/libc    ( 4900): [NET] getaddrinfo+,hn 14(0x3130342e313534),sn(),family 0,flags 4
,D/libc    ( 4900): [NET] getaddrinfo-, SUCCESS
,I/MyReportAgent( 4900): CSUploader returned value : 200 , TAG:HTC_ULOGDATA
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.reportagent (4900/10065)
,D/PMS     (  904): releaseWL(42325810): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 null
,V/MyReportAgent( 4900): Utils getType(): 1, getSubtype: 0
,D/MyReportAgent( 4900): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.reportagent (4900/10065)
,D/MyReportAgent( 4900): ReportUploader Start upload resuming queue files. file count: 63
,D/MyReportAgent( 4900): ReportUploader resume file: 0000014ff6b9608e-HTC_ULOGDATA-USAGE-36bc5585-d263-4808-9e6c-c3332f52dfd5
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.reportagent (4900/10065)
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.reportagent (4900/10065)
,D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.reportagent (4900/10065)
,D/Pomelo  ( 4900): LogLib params context = android.app.Application@420fd0c8	isDebug = false	isEngineerROM = false
D/PomeloConfig( 4900): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4900): LogLibStore version is 1.3
D/PomeloConfig( 4900): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
D/PomeloConfig( 4900): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
D/PomeloConfig( 4900): loadFromPreference(), RefreshInterval = 604800
,D/Pomelo  ( 4900): sendLogEnvelope envelope valid
,D/Pomelo  ( 4900): inBytes=[767704]
,D/Pomelo  ( 4900): outBytes.length=[21029]
D/libc    ( 4900): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4900): [NET] getaddrinfo-,err=8
D/libc    ( 4900): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4900): [NET] getaddrinfo-, 1
D/libc    ( 4900): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =99a1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4900): [NET] getaddrinfo_proxy-, success
I/global  ( 4900): call createSocket() return a new socket.
D/libc    ( 4900): [NET] getaddrinfo+,hn 14(0x3130342e313534),sn(),family 0,flags 4
,D/libc    ( 4900): [NET] getaddrinfo-, SUCCESS
,I/MyReportAgent( 4900): CSUploader returned value : 503 , TAG:HTC_ULOGDATA
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.reportagent (4900/10065)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.reportagent (4900/10065)
,D/MyReportAgent( 4900): break resuming queue files
,V/MyReportAgent( 4900): ReportServiceHandler register the PowerConnected Listener
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=1, flag=1, pid=4900, uid=10065, userID:0
,D/MyReportAgent( 4900): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@421026d8
,D/Process (  904): killProcessQuiet, pid=4122
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4122:com.android.vending/u0a73 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4122
,D/PMS     (  904): acquireWL(445c4460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(445c4460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/PMS     (  904): acquireWL(4335d758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4335d758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(428f3598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1381660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428f3598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(434c9de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(434c9de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42947f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42947f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  904): acquireWL(434167e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1441660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(434167e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42af46a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/BatteryService(  904): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(42af46a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43226e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43226e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42b21320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1501660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b21320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(429dcbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(429dcbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42923d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42923d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43ae4a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1561659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ae4a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42af71d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42af71d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ab5308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  904): releaseWL(42ab5308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(446773c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1621659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(446773c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(431997b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(431997b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44658cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44658cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42c22a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1681660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42c22a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44098f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(44098f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44132fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(44132fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43ae3918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1741660, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ae3918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(437b78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437b78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42c7a200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42c7a200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43ae48d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1801659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ae48d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f06f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f06f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(4348e370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4259e3e0: PendingIntentRecord{42136cd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1861659, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  904): Prepared write state in 40ms
,I/ProcessStatsService(  904): Prepared write state in 18ms
,D/PMS     (  904): releaseWL(4348e370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2016-01-04-03-41-04.bin
,D/PMS     (  904): acquireWL(446c63f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(446c63f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42b08590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42b08590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1592): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1592): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  904): Killing 4534:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1808s
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/Process (  904): killProcessQuiet, pid=4534
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/PMS     (  904): acquireWL(446e1dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423f2900: PendingIntentRecord{42a2ed18 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1732440, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{4297a9d0: PendingIntentRecord{42ad5300 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821023, Int=1800000
V/AlarmManager(  904): sending alarm PendingIntent{43ae4720: PendingIntentRecord{42aceb20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912562, Int=0
D/PMS     (  904): acquireWL(43521b80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
V/AlarmManager(  904): sending alarm PendingIntent{42c3b5d0: PendingIntentRecord{42c4eda0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451956119063, Int=900000
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): releaseWL(43521b80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  904): acquireWL(438450c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1368 10028 null
,D/PMS     (  904): releaseWL(438450c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  904): acquireWL(438a5b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,W/ContextImpl( 4772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(438a5b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  904): releaseWL(446e1dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,I/ActivityManager(  904): Recipient 4534
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/Process (  904): killProcessQuiet, pid=4160
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  904): killProcessQuiet, pid=4729
I/ActivityManager(  904): Killing 4160:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
,I/ActivityManager(  904): Killing 4729:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  904): killProcessQuiet, pid=4714
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4714:com.android.chrome/u0a96 (adj 15): empty for 1800s
,D/Process (  904): killProcessQuiet, pid=4698
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  904): killProcessQuiet, pid=1404
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4698:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
I/ActivityManager(  904): Killing 1404:com.htc.sense.hsp/u0a53 (adj 15): empty for 1800s
,I/ActivityManager(  904): Recipient 4729
I/ActivityManager(  904): Recipient 4698
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4714
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4160
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 1404
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4944): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4944): ====startRecUseTime====
D/htc.customization.log.level( 4944):  is 
W/CustomizationLogLevel( 4944): Level value is invalid, use default level 2
D/CustomizationManager( 4944):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4944): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4944): Parsing tag category name = system
I/CustomizationCIDLoader( 4944): Parsing tag category name = application
I/CustomizationCIDLoader( 4944): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4944): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4944): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4944): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4944): Parsing tag category name = Settings
D/CustomizationManager( 4944):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4944):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4944): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4944): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4944): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4944): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4944, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  904): Copying FileAsset 0x676dcb28 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  904): Skipping PackageSetting{42849d88 com.example.hello/10356} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/Process (  904): killProcessQuiet, pid=4603
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 4603:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  904): Recipient 4603
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.music (pid 4603): Died!
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1592): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1592): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1592): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/acms    ( 1921): Unregistering com.test.thalitest
E/acms    ( 1921): Could not unregister removed application com.test.thalitest
W/BroadcastQueue(  904): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  904): android.os.DeadObjectException
W/BroadcastQueue(  904): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  904): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  904): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  904): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  904): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
W/GeofencerStateMachine( 1430): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(446c8ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  904): releaseWL(446c8ef0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
D/PackageBroadcastService( 2229): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4958 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/MultiDex( 4958): install
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1246 :
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4973 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1246): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4958): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 2229): CP2 sync disabled
I/MultiDex( 4958): loading existing secondary dex files
I/MultiDex( 4958): load found 1 secondary dex files
I/MultiDex( 4958): install done
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2229, uid=10028, userID:0
I/Icing   ( 2229): doRemovePackageData com.test.thalitest
D/PMS     (  904): acquireWL(425cdc40): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
I/ProviderInstaller( 4958): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  904): releaseWL(425cdc40): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4973): install
I/MultiDex( 4973): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4973): loading existing secondary dex files
I/MultiDex( 4973): load found 1 secondary dex files
I/MultiDex( 4973): install done
I/ProviderInstaller( 4973): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4994 uid=10053 gids={50053, 1023, 3003, 5012}
E/SQLiteDatabase( 4958): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4958): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4958): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4958): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4958): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4958): threadid=12: thread exiting with uncaught exception (group=0x41cc3e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 4958): killProcess, pid=4958
D/Process ( 4958): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4958): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4958): Process: com.google.android.gms.drive, PID: 4958
E/AndroidRuntime( 4958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4958): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4958): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4958): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4958): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/PluginProvider( 4994): PluginProvider onCreate
E/SQLiteDatabase( 4994): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4994): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4994): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4994): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4994): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4994): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4994): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4994): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4994): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4994): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4994): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4994): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4994): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4994): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4994): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4994): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4994): Opened registry.db in read-only mode
D/PluginProvider( 4994): current plugin count: 19
D/HtcAppUPService( 4994): HtcUPDataProvider onCreate()
I/ActivityManager(  904): Recipient 4958
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4958) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/PackageManager(  904): Unable to load service info ResolveInfo{42bb8638 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
I/[PluginManager]RegisterService( 4994): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4994): provider may killed!
W/[PluginManager]RegisterService( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4994): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4994): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4994): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4994): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4994): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4994): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4994): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4994): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5009 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5009, uid=10073, userID:0
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/Finsky  ( 5009): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (5009/10073)
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (5009/10073)
D/Finsky  ( 5009): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 5009): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5009): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 5009): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5009): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5009): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 5009): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 5009): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 5009): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5009): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5009): threadid=25: thread exiting with uncaught exception (group=0x41cc3e30)
E/ActivityManager(  904): App crashed! Process: com.android.vending
E/AndroidRuntime( 5009): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5009): Process: com.android.vending, PID: 5009
E/AndroidRuntime( 5009): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5009): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 5009): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 5009): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 5009): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5009): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5009, uid=10073, userID:0
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 5009): killProcess, pid=5009
D/Process ( 5009): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  904): Recipient 5009
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.vending (pid 5009) has died.
I/IcingCorporaProvider( 2905): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5042 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2905): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2905): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644af1b0
W/dalvikvm( 2905): threadid=14: thread exiting with uncaught exception (group=0x41cc3e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2905): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2905): Process: com.google.android.googlequicksearchbox:search, PID: 2905
E/AndroidRuntime( 2905): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2905): 	at cid.d(PG:186)
E/AndroidRuntime( 2905): 	at clo.g(PG:594)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2905): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2905): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2905): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2905): 	at clr.tL(PG:827)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2905): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2905): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2905): killProcess, pid=2905
D/Process ( 2905): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/ActivityManager(  904): Recipient 2905
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2905) has died.
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2905): Died!
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 5042): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5042): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5042): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5042): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5042): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5042): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5042): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5042): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5042): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5042): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5042): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5042): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5042): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5042): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5042): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5042): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5042): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5042): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5042): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5042): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5042): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5042): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5042): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5042): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5042): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5042): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5042): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5042): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5042): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5042): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5042): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5042): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5042): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5042): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5042): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5042): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5042): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5042): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5042): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5042): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5042): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5042): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5042): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5042): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5042): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5042): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5042): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5042): threadid=11: thread exiting with uncaught exception (group=0x41cc3e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5042): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5042): Process: com.google.android.apps.docs, PID: 5042
E/AndroidRuntime( 5042): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5042): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5042): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5042): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5042): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5042): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5042): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5042): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5042): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
D/Process ( 5042): killProcess, pid=5042
D/Process ( 5042): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5058 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 5042
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 5042) has died.
W/ContextImpl( 5058): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 

```
