#### Test 543122982543be8_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  909): acquireWL(42820e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
--------- beginning of /dev/log/main
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42820e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/cutils-trace( 4399): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4399): ====startRecUseTime====
D/htc.customization.log.level( 4399):  is 
W/CustomizationLogLevel( 4399): Level value is invalid, use default level 2
D/PMS     (  909): acquireWL(425d85f0): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
D/CustomizationManager( 4399):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4399): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4399): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4399): Parsing tag category name = system
I/CustomizationCIDLoader( 4399): Parsing tag category name = application
I/CustomizationCIDLoader( 4399): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4399): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4399): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4399): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4399): Parsing tag category name = Settings
D/CustomizationManager( 4399):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4399):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4399): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4399): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4399): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4399): Fail to get flag for type 'language', use default value: -1
D/PMS     (  909): releaseWL(425d85f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  909): acquireWL(425b1d88): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4399
D/PMS     (  909): acquireHCC(425058b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(4247d630): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/SensorManager(  909): mEventCount = 1200
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1113677592
D/PMS     (  909): acquireWL(4216d9f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ee3188
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4414 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
D/PMS     (  909): releaseWL(425b1d88): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4414): Binding Chromium to main looper Looper (main, tid 1) {41ca8698}
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
I/chromium( 4414): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4414): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(43080518): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424c51a0:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4414): 1103880400: getState(). Returning 12
D/PMS     (  909): acquireWL(42f01fb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): releaseWL(43080518): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
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
,I/InputMethodManagerService(  909): Disable input method client, pid=1273
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41cef780, mServedView=org.apache.cordova.engine.SystemWebView{41cb53e8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  909): Enable input method client, pid=4414
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +297ms
,D/PMS     (  909): releaseWL(4216d9f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4414): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4414): JniHelper::setJavaVM(0x41865010), pthread_self() = 1663086760
,D/JX-Cordova( 4414): jxcore cordova android initializing
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4459 uid=10077 gids={50077}
,D/PMS     (  909): acquireWL(41d686a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
V/AlarmManager(  909): sending alarm PendingIntent{4259df30: PendingIntentRecord{427400b0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450745454391, Int=60000
,D/PMS     (  909): releaseWL(41d686a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4459): SMSBackupAgentService started
,D/SMSBackup( 4459): Checking restore status
D/SMSBackup( 4459): Restore complete
,D/SMSBackup( 4459): cancelCheckAlarm
,D/SMSBackup( 4459): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=3250
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3250:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3250
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.548MB for 96598-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.633MB for 144892-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.756MB for 217334-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.933MB for 325996-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.192MB for 488990-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 13.199MB for 1100216-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 14.088MB for 1650320-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 15.444MB for 2475476-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
,D/PMS     (  909): releaseHCC(425058b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(4247d630): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 17.544MB for 3713210-byte allocation
,W/jxcore-log( 4414): Initializing JXcore engine
,W/jxcore-log( 4414): JXcore engine is ready
,W/jxcore-log( 4414): Starting JXcore engine
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
,W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=38 rxSum=29} preTxRxSum={txSum=37 rxSum=28}
,D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
D/PMS     (  909): acquireWL(4254b830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{426db4a0: PendingIntentRecord{424de948 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105567, Int=0
,D/PMS     (  909): releaseWL(4254b830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19440 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19441 delay=15s
,D/PMS     (  909): releaseWL(42f01fb8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,I/chromium( 4414): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:68, mTXpacketCount:68, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4414): Toggling radios to true
I/jxcore-log( 4414): 
,D/BluetoothAdapter( 4414): enable(): BT is already enabled..!
,D/WifiManager( 4414): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
,W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1354
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
D/WifiService(  909): setWifiEnabled: true pid=4414, uid=10348
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  909): New client listening to asynchronous messages
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiManager( 4414): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4414): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4414): Radios toggled
I/jxcore-log( 4414): 
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4414): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4414): 
I/jxcore-log( 4414): Perf Test app loaded loaded
I/jxcore-log( 4414): 
I/Choreographer( 4414): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4414): check test folder
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): found test : ./testFindPeers.js
I/jxcore-log( 4414): 
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1164): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b3dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700,
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false,
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
I/jxcore-log( 4414): found test : ./testSendData.js
I/jxcore-log( 4414): 
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/DhcpStateMachine(  909): [RunningState] Stop DHCP
,D/PMS     (  909): acquireWL(41de2420): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19441 mDataStallAlarmIntent=PendingIntent{4218d820: PendingIntentRecord{424de948 android broadcastIntent}}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): Fast associate: Old scan results
I/wpa_supplicant( 1164): wpa_supplicant_scan enter
I/wpa_supplicant( 1164): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1164): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1164): wpa_supplicant_trigger_scan +
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1164): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1164): nl80211: Event message available
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1164): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  909): isAvailable+-
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiP2pService(  909): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  909): New client listening to asynchronous messages
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  909): acquireWL(4276c1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:5   entry:0xb70be818  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb70be2d8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb70be108  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb70bdec0  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb70be1d0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb70be410  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(423b42c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,I/jxcore-log( 4414): found test : ./testSendData2.js
I/jxcore-log( 4414): 
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:3
,D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  909): acquireWL(426dfb78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/WifiNative-wlan0(  909): doBoolean: SCAN
D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  909):    returned false
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  909): releaseWL(426dfb78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
D/PMS     (  909): releaseWL(423b42c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  909): releaseWL(4276c1c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,I/chromium( 4414): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(424e46a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
,D/PMS     (  909): releaseWL(424e46a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178),
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1500/10028)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3871/10154)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  909): bSetPropertyMultiRAB:false
I/NetworkMonitor( 3871): type=WIFI subType= reason=null isConnected=false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4299/10100)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2453/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4481 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4481): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4481): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4481): Preparing secondary program dexes.
V/DexLibLoader( 4481): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4481): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4481): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4481): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4481): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4481): Creating class loader
V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4481): Creating class loader
,V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4481): Creating class loader,
V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4481): Creating class loader
,V/DexLibLoader( 4481): Finished creating class loader
,V/DexLibLoader( 4481): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4481): DexLibLoader.ensureDexLoaded took 20 ms
,D/PMS     (  909): acquireWL(431e8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109354, Int=0
,D/PMS     (  909): releaseWL(431e8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1117): now=1450745460055 next=59945
,W/dalvikvm( 4481): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1164): nl80211: Event message available
D/wpa_supplicant( 1164): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1164): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1164): nl80211: Survey data missing
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1164): Sorted scan results
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1164): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1164): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1164): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1164): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1164): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1164): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1164): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1164): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1164): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1164): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1164): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1164): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1164): wpa_supplicant_pick_network+
I/wpa_supplicant( 1164): Selecting BSS from priority group 1
I/wpa_supplicant( 1164): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1164): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1164): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1164): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1164):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1164):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1164): Start print parameters
I/wpa_supplicant( 1164): wpa_s->wpa_state is 3
I/wpa_supplicant( 1164): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1164): isConcurrentMode() is 0
I/wpa_supplicant( 1164): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1164): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1164): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1164): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1164): wpa_s->reassociate is 1
I/wpa_supplicant( 1164): wpa_s->is_screen_on 1
I/wpa_supplicant( 1164): wpa_s->ifname wlan0
I/wpa_supplicant( 1164): End print parameters
I/wpa_supplicant( 1164): selected network = 1
D/wpa_supplicant( 1164): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b3f4e8  current_ssid=0x0
D/wpa_supplicant( 1164): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1164): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1164): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1164): check if in concurrent case
I/wpa_supplicant( 1164): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/dalvikvm( 4481): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate, incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1164): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1164): RSN: PMKSA cache search - network_ctx=0xb8b3f4e8 try_opportunistic=0
D/wpa_supplicant( 1164): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1164): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb8b3e718 (mode change)
D/wpa_supplicant( 1164): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b3e718
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Register frame type=0xd0 nl_handle=0xb8b3e718
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1164): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1164):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1164):   * freq=2412
D/wpa_supplicant( 1164):   * Auth Type 0
D/wpa_supplicant( 1164):   * WPA Versions 0x2
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1164): nl80211: Connect request send successfully
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1164): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1164): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1164): reply (617) for get BSS: id=0
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1164): freq=5220
I/wpa_supplicant( 1164): level=-48
I/wpa_supplicant( 1164): tsf=0000000109831136
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG7005g
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=1
I/wpa_supplicant( 1164): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000109831155
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1164): ssid=NG700
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=2
I/wpa_supplicant( 1164): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): freq=2412
I/wpa_supplicant( 1164): level=-50
I/wpa_supplicant( 1164): tsf=0000000109831149
I/wpa_supplicant( 1164): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1164): ssid=01ABC
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=3
I/wpa_supplicant( 1164): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-88
I/wpa_supplicant( 1164): tsf=0000000109831159
I/wpa_supplicant( 1164): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=UPC Wi-Free
I/wpa_supplicant( 1164): ====
I/wpa_supplicant( 1164): id=4
I/wpa_supplicant( 1164): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1164): freq=2462
I/wpa_supplicant( 1164): level=-90
I/wpa_supplicant( 1164): tsf=0000000109831163
I/wpa_supplicant( 1164): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1164): ssid=UPC0039325
I/wpa_supplicant( 1164): ####
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (5) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 109831136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 109831155, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 109831149, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 109831159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 109831163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 5 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,E/FbInjectorInitializer( 4481): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1164): nl80211: Event message available
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1164): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1164): nl80211: Connect event
D/wpa_supplicant( 1164): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1164): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1164): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1164): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): Add randomness: count=10 entropy=5
I/wpa_supplicant( 1164): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1164): TDLS: Remove peers on association
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1164): EAPOL: enable timer tick
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): Get randomness: len=32 entropy=6
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:g,etSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b3e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1164): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ecbb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1164):    broadcast key
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 11
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1164): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1164): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1164): wlan0: Connect to SSID: NG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1164): set send_ind_to_ndc = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1164): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1164): EAPOL authentication completed successfully
I/wpa_supplicant( 1164): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1164): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1164): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1164): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4193): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4193): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 1
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(431ecb28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42556a70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42556a70 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4481): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42335f80
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
,W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42335f80, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4250b150
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@4282b2f0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=4239
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4239:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  909): acquireWL(44294998): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
,I/ActivityManager(  909): Recipient 4239
,D/WifiService(  909): Client connection lost with reason: 4
,D/PMS     (  909): acquireWL(440e5870): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2256 10028 null
,D/PMS     (  909): releaseWL(44294998): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
D/PMS     (  909): releaseWL(440e5870): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1413): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4511 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
,D/AutoSetting( 1413): Util - no network available!
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
D/AutoSetting( 1413): service - onCreate()
D/AutoSetting( 1413): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  909): request 426e4778 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1413): service - mHandler: cancel location update
,D/AutoSetting( 1413): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4481): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,I/SensorManager(  909): mEventCount = 1350
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4,
D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4,
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0,
,I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  909): releaseWL(431ecb28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 373ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): nativeSetAutoSuspend:true done
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  909):    returned true
,D/NfcService( 1259): ScreenObserver: OFF
D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/NfcService( 1259): applyRouting - 0
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/NfcService( 1259): applyRouting -2
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/PMS     (  909): OOBE c monitor 11
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4414
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/PMS     (  909): acquireWL(4417cfd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42504ca0)
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41cb53e8 VFEDH.C. .F...... 0,0-720,1134 #64}
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19443 delay=15s
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): releaseWL(4417cfd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  909): onScreenOn
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  909): acquireWL(43f70c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43f70c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  909): WAN detection
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WISPrService( 4193): >>>>>WISPrService start isConnected = true<<<<<
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
,D/HtcPowerSaver(  909): updateBatteryInfo
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/MtpService( 2453): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2453): [MTP][onReceive]-
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): syncGetConfiguredNetworks
,D/NfcService( 1259): applyRouting - 0
,D/NfcService( 1259): applyRouting -2
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@425d64e0
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): acquireWL(43765210): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  909): releaseWL(43765210): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/HtcPowerSaver(  909): << updateStatus
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19444 delay=15s
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): SET_SCREEN_ON:On
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(441b5250): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/MobileConnectivityChangeReceiver( 4511): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
D/MobileConnectivityChangeReceiver( 4511): onReceive CONNECTIVITY_CHANGE networkType=1
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  909): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
E/PhoneMonitor( 4511): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4511): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/ClockThread( 1117): stop update clock
I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4559 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10078)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,V/SRS_Proc(  371): ParamSet string: screen_state=on
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10078)
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10078)
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4481): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10078)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.962MB for 84664-byte allocation
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4481): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4481): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4481): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/PMS     (  909): releaseWL(441b5250): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/NetworkPolicy(  909): updateScreenOn: false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4579 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3856
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3856:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.977MB for 28144-byte allocation
E/dalvikvm( 4481): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4481): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1835): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1835): onScreenOn: 1450745461509
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1835): onScreenOn: 1450745461509
D/PMS     (  909): acquireWL(43ad9af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1500 10028 null
D/PMS     (  909): releaseWL(43ad9af8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4250b150
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4250b150, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@4282b2f0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  909): acquireWL(43d46fb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(44189c58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
D/PMS     (  909): acquireWL(4419f7b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2256 10028 null
D/PMS     (  909): releaseWL(43d46fb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/PMS     (  909): releaseWL(44189c58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,I/CheckinService( 2256): Preparing to send checkin request
,I/EventLogService( 2256): Accumulating logs since 1450745404992
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.018MB for 39954-byte allocation
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/GoogleHttpClient( 2256): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2256): Using GMS GoogleHttpClient,
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4579): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/wpa_supplicant( 1164): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1164): EAPOL: disable timer tick
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2256/10028)
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  909): Recipient 3856
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (2256/10028)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2256): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ccf648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
V/WebViewChromiumFactoryProvider( 4579): Binding Chromium to main looper Looper (main, tid 1) {41cad208}
I/LibraryLoader( 4579): Expected native library version number "",actual native library version number ""
I/RemoteViews.Performance( 1117): com.google.android.gms 1 9 3 12
I/chromium( 4579): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4579): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/PMS     (  909): acquireWL(43859510): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): releaseWL(43859510): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  909): acquireWL(43ad40a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4603 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/AudioManagerAndroid( 4579): BLUETOOTH permission is missing!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43996f08 u0 ReceiverList{43996de8 4481 com.facebook.katana/10026/u0 remote:43846c60}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43996f08 u0 ReceiverList{43996de8 4481 com.facebook.katana/10026/u0 remote:43846c60}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441546a8 u0 ReceiverList{44154648 4481 com.facebook.katana/10026/u0 remote:4411ba98}}
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4603): install
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
I/MultiDex( 4603): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4603): loading existing secondary dex files
I/MultiDex( 4603): load found 1 secondary dex files
I/MultiDex( 4603): install done
,I/NSApplication( 4579): Starting up...
D/PMS     (  909): acquireWL(43d186e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1500 10028 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19444 mDataStallAlarmIntent=PendingIntent{42c76970: PendingIntentRecord{424de948 android broadcastIntent}}
,I/ProviderInstaller( 4603): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
D/PMS     (  909): releaseWL(43d186e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
D/PMS     (  909): acquireWL(433b3510): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): SET_SCREEN_ON:Off
I/wpa_supplicant( 1164): htc_wext_set_keepalive +
I/wpa_supplicant( 1164): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1164): getPrivFuncNum +	
I/wpa_supplicant( 1164): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1164): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1164): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1164): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1164): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/Process (  909): killProcessQuiet, pid=4269
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  909): Killing 4269:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,V/SRS_Proc(  371): ParamSet string: screen_state=off
I/ActivityManager(  909): Recipient 4269
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1247): start background delete task...
,D/GCoreFlp( 1500): Unknown pending intent to remove.
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
D/PMS     (  909): acquireWL(4272fdf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1500 10028 null
D/PMS     (  909): releaseWL(4272fdf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/PMS     (  909): releaseWL(433b3510): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1413): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] getTotalRam: 1873 Mb
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/TetherSettings( 4193): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4193): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4193): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4193): Cust_ConnectToPC   : spcsc>false
D/        ( 4193): Cust_ConnectToPC   : IPT>true
,D/        ( 4193): Cust_ConnectToPC   : Singel_USB>false
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Settings( 4193): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
E/SmartNS_Utility( 4193): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4193): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4193): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/PSReceiver( 4193): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1835): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1835): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1835): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1835): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1835): onScreenOff
D/PMS     (  909): acquireWL(43409380): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1500 10028 null
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
D/PMS     (  909): releaseWL(43409380): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 4193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4193): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4193): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4193):  defaultType:0
,D/AutoSetting( 1413): service - mHandler: cancel location update
,D/AutoSetting( 1413): service -           changes count: 0
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4644 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(44320ff8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4644 1000 null
,D/PMS     (  909): releaseWL(44320ff8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4644): getMobilePolicyEnabled, result = true
,D/Process (  909): killProcessQuiet, pid=4299
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Killing 4299:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4644): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4282b2f0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4282b2f0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4282b2f0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4282b2f0
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4282b7e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4282b7e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  909): Recipient 4299
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  909): releaseWL(41de2420): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1500/10028)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3871/10154)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
,I/NetworkMonitor( 3871): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  909): bSetPropertyMultiRAB:false
I/acms    ( 1895): Checking Certificates
I/acms    ( 1895): Checking Developer Certificates
I/acms    ( 1895): Checking Application Certificates
I/acms    ( 1895): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1895): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1895): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1895): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1895): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1895): Updating next query delay: 75600000
I/mlserverapp( 1895): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1895): cancelACMSProgrammedChecks
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3895/10051)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(439835c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4511/10078)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  909): acquireWL(438a07d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2453/10021)
D/PMS     (  909): releaseWL(438a07d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/PMS     (  909): releaseWL(439835c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,D/PMS     (  909): acquireWL(420776c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2256 10028 null
,D/PMS     (  909): releaseWL(420776c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  909): acquireWL(4312b2e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1371 10028 null
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1371): [NET] getaddrinfo-, 1
D/libc    ( 1371): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3397 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/AutoSetting( 1413): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4511): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4511): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
,D/AutoSetting( 1413): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1371): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 1413): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4579/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1413/10053)
D/AutoSetting( 1413): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1413): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4168/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1857/10178)
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  909): acquireWL(4243e690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(4243e690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4603/10028)
,D/GCM     ( 1371): Connected
,D/PMS     (  909): acquireWL(424b22f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): releaseWL(4312b2e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): releaseWL(424b22f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(433fade0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1371): Message class mpf
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/PMS     (  909): releaseWL(433fade0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): acquireWL(431203c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(431203c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4603): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2256): Sending checkin request (9009 bytes)
D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2256): [NET] getaddrinfo-,err=8
D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2256): [NET] getaddrinfo-, 1
,D/libc    ( 2256): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4130 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 210
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2256): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2256): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2256): [NET] getaddrinfo-,err=8
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,W/dalvikvm( 4414): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4414): threadid=1: thread exiting with uncaught exception (group=0x41876e30)
,E/ActivityManager(  909): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4414): FATAL EXCEPTION: main
E/AndroidRuntime( 4414): Process: com.test.thalitest, PID: 4414
E/AndroidRuntime( 4414): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4414): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4414): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4414): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
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
W/ActivityManager(  909):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  909): killProcessQuiet, pid=4322
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  909): Killing 4322:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  909): Recipient 4322
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4414): killProcess, pid=4414
,D/Process ( 4414): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=10 [20][2][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4414 uid 10348
E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4414
,I/ActivityManager(  909): Process com.test.thalitest (pid 4414) has died.
,I/WindowState(  909): WIN DEATH: Window{425777c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  909): Client connection lost with reason: 4
,D/PMS     (  909): acquireWL(42e99538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(42e99538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2256/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (2256/10028)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/CheckinRequestBuilder( 2256): awaiting user notification for token
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42138d18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 7 2 12
,I/CheckinTask( 2256): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2256): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/PMS     (  909): releaseWL(4419f7b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/ActivityThread( 2256): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41de7840 that was originally bound here
E/ActivityThread( 2256): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41de7840 that was originally bound here
E/ActivityThread( 2256): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2256): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2256): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2256): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2256): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2256): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2256): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2256): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2256): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2256): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2256): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2256): 	at bks.a(SourceFile:298)
E/ActivityThread( 2256): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2256): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2256): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2256): 	at java.lang.Thread.run(Thread.java:864)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,I/GCM     ( 1371): GCM config loaded
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4481): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8bf5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/104.81.130.175,
,D/PMS     (  909): releaseWL(43ad40a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/AutoSetting( 1470): service - handleMessage() stop self
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/AutoSetting( 1470): service - onDestroy() END
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1470): service - handleMessage() quit looper
,I/GAV2    ( 4579): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(435b7a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1500 10028 null
,D/PMS     (  909): acquireWL(439c8f10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1500 10028 null
,D/PMS     (  909): releaseWL(435b7a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  909): releaseWL(439c8f10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  909): killProcessQuiet, pid=4286
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4286:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4286
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  909): killProcessQuiet, pid=3895
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3895
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43690b00 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  909): acquireWL(426bfc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(426bfc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(44149858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42599f68: PendingIntentRecord{42690d38 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140901, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{420bde80: PendingIntentRecord{427385c0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141232, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(427d7898): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  909): releaseWL(44149858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  909): acquireWL(441d87f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  909): releaseWL(441d87f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2845 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/PMS     (  909): acquireWL(43208028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43208028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1413): service - has update message, not stop
,D/AutoSetting( 1413): service - mHandler: update timezone
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1470): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1470): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1470): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1470): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1470): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  909): batLight: Full, plugged
,V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
,D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1585): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1470): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1470): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1470): service - mHandler: update timezone
,D/AutoSetting( 1470): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1470): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1470): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1470): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41feb850 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 4 9 3 11
,D/PMS     (  909): releaseWL(427d7898): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{44222fb8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(427b9bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427b9bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1413): service - handleMessage() stop self
,D/AutoSetting( 1413): service - handleMessage() quit looper
,D/AutoSetting( 1413): service - onDestroy() END
,D/AutoSetting( 1470): service - handleMessage() stop self
,D/AutoSetting( 1470): service - onDestroy() END
,D/AutoSetting( 1470): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4340
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4340:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4340
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(44294fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(44294fe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(433719b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(433719b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43934ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43934ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43738a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{436d9978: PendingIntentRecord{42c48098 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231095, Int=0
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4703 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{42564510: PendingIntentRecord{428255e8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450745570550, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{436ad490: PendingIntentRecord{42c48098 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231136, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{44100550: PendingIntentRecord{441d4450 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231141, Int=120000
,D/PMS     (  909): releaseWL(43738a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4703/10047)
,D/Process (  909): killProcessQuiet, pid=4356
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4356:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4356
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(434c8e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434c8e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43d42ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d42ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(42c7d4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=289355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42c7d4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(435f9d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(435f9d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(43ddbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=349354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ddbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43080e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{448362b0: PendingIntentRecord{437d5da8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450745709029, Int=0
,D/PMS     (  909): releaseWL(43080e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2256): No account for auth token provided
,D/libc    ( 2256): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2256): [NET] getaddrinfo-,err=8
D/libc    ( 2256): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2256): [NET] getaddrinfo-, 1
,D/libc    ( 2256): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5ff2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 112
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2256): [NET] getaddrinfo_proxy-, success
I/global  ( 2256): call createSocket() return a new socket.
D/libc    ( 2256): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2256): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2256): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2256): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1371): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1371): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1371): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1371): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1371): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1371): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1371): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1371): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cb6408 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4132): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4132): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4132): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4132): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4132): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 9 4 12
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4132): [NET] getaddrinfo-,err=8
D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4132): [NET] getaddrinfo-, 1
,D/libc    ( 4132): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =39a4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4132): [NET] getaddrinfo_proxy-, success
I/global  ( 4132): call createSocket() return a new socket.
D/libc    ( 4132): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4132): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4132): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(4369a1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4369a1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4378f6c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=409355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4378f6c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(436594f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436594f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(440df7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(440df7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(4417a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=469355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4417a6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(440a7bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(440a7bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(44177718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=529355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44177718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43406d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43406d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a719b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a719b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4280d1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=589355, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4280d1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d88ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d88ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1247): sku_id=99
D/ContactMessageStore( 1247): start background delete task...
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/PMS     (  909): acquireWL(4262f828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4262f828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43534f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=649355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43534f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4418bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4418bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42e4b758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=709355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42e4b758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  909): killProcessQuiet, pid=4371
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4371:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4371
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(4419b830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{427ed0d8: PendingIntentRecord{441d4450 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531158, Int=300000
,V/AlarmManager(  909): sending alarm PendingIntent{441f8398: PendingIntentRecord{426cd7d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450746073522, Int=0
,D/PMS     (  909): releaseWL(4419b830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4132): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4132): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4132): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4132): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4132): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/PMS     (  909): acquireWL(42807910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42807910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43d4ccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{41ee0518: PendingIntentRecord{43dab970 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450746088716, Int=0
,D/PMS     (  909): releaseWL(43d4ccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4132): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  909): acquireWL(42ed4bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=769355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ed4bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4428b688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  909): sending alarm PendingIntent{41f63050: PendingIntentRecord{425e0c98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785918, Int=0
,D/PMS     (  909): releaseWL(4428b688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds,
,D/PMS     (  909): acquireWL(42870558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42870558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42e5ed90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42e5ed90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4193): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4193): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4193): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4193): Cust_ConnectToPC   : spcsc>false
D/        ( 4193): Cust_ConnectToPC   : IPT>true
D/        ( 4193): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4193): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4193): Index of the first 1 = 3
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
W/ContextImpl( 4193): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4193): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4193): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4193): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4193): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4193): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4193): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44246ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=829354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44246ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4411b5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4411b5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4250f2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4250f2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4412f670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=889354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4412f670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a497a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/PMS     (  909): releaseWL(43a497a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43933750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43933750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43d73f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=949354, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43d73f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43ddef80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43ddef80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43426950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43426950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(441f48e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1009354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(441f48e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4393ecb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4269c5b8: PendingIntentRecord{426a8f60 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450746291160, Int=900000
,W/ContextImpl( 4644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  909): sending alarm PendingIntent{444a6d60: PendingIntentRecord{435837e0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1450746338532, Int=84918423
,V/AlarmManager(  909): sending alarm PendingIntent{4282e510: PendingIntentRecord{441b89c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450746362097, Int=0
D/PowerUsageService( 4644): call getInstance()
D/SmartSyncUtils( 4644): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4644): MY_DEBUG = false
D/PMS     (  909): acquireWL(43203db8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4644 1000 null
D/PMS     (  909): releaseWL(4393ecb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2256/10028)
D/SmartSyncScreenOnOffTimeReceiver( 4644): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4644): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4644): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4644): SettingOnTime = 1450821600000, randomSettingOnTime = 1450820042000
D/SmartSyncScreenOnOffTimeReceiver( 4644): SettingOffTime = 1450810800000, randomSettingOffTime = 1450813658000
D/SmartSyncScreenOnOffTimeReceiver( 4644): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4644): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4644): bNightModeTurnOffOnce = false
,D/SnetService( 2256): snet destroyed
W/BatSI   (  909): Couldn't get kernel wake lock stats
D/PMS     (  909): releaseWL(43203db8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(41ca7b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(41ca7b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42e96438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42e96438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(427b2670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1069355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427b2670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(424f9d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(424f9d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(426e78b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426e78b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(431ea2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1129354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431ea2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43999c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43999c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(426c49c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(426c49c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42d6a490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1189354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d6a490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d48d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PMS     (  909): releaseWL(43d48d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(441a5c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(441a5c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4380b948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{4266aca0: PendingIntentRecord{427410c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012194, Int=0
,D/PMS     (  909): acquireWL(4428b608): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1371 10028 null
,V/AlarmManager(  909): sending alarm PendingIntent{437345c8: PendingIntentRecord{4254d910 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450746564146, Int=1800000
,D/PMS     (  909): releaseWL(4428b608): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  909): acquireWL(437a6688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(437a6688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): acquireWL(444a6910): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2256 10028 null
,D/PMS     (  909): releaseWL(4380b948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): acquireWL(4373b928): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2256 10028 null
,D/PMS     (  909): releaseWL(444a6910): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 2256): Aggregate from 1450745461543 (log), 1450744764098 (data)
,D/PMS     (  909): releaseWL(4373b928): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  909): acquireWL(4422a770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
,D/GCM     ( 1371): Message class mow
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  909): acquireWL(42326ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  909): releaseWL(4422a770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  909): releaseWL(42326ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=5 [157][9][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(433f14f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1249355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(433f14f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(427be058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  909): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PMS     (  909): releaseWL(427be058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44293e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44293e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(438e48d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1309354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(438e48d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(426cbef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426cbef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42870430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(42870430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436550b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1369354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(436550b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43af2620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43af2620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436e7068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436e7068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  909): << updateStatus
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428200a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1429355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428200a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4312b7b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4312b7b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4352d480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4352d480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(441f6e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1489354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(441f6e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437320c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41f63050: PendingIntentRecord{425e0c98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505939, Int=0
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): releaseWL(437320c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,D/PMS     (  909): acquireWL(43277158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43277158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4413cc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4413cc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42b06df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1549354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42b06df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(426c2500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426c2500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(431f4740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(431f4740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42d57930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1609354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d57930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(441c7cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(441c7cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(433c3838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(433c3838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43274678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1669354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43274678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437450b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(437450b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(432c8458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(432c8458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4308d5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1729355, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4308d5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(436c44f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436c44f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42807f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42807f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(433e15b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1789354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(433e15b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(44103ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(44103ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(43d7ea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  909): releaseWL(43d7ea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(433d35a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1849354, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  909): Prepared write state in 29ms
,D/PMS     (  909): releaseWL(433d35a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-12-21-08-09-00.bin
,D/PMS     (  909): acquireWL(43903908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(43903908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(431746a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(431746a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43ae3818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d9f658: PendingIntentRecord{41d9efb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1909354, Int=0
,D/Process (  909): killProcessQuiet, pid=4459
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  909): killProcessQuiet, pid=4017
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4459:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1805s
I/ActivityManager(  909): Killing 4017:com.google.android.gm/u0a107 (adj 15): empty for 1833s
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  909): Recipient 4459
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(43ae3818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  909): Recipient 4017
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4782): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4782): ====startRecUseTime====
D/htc.customization.log.level( 4782):  is 
W/CustomizationLogLevel( 4782): Level value is invalid, use default level 2
D/CustomizationManager( 4782):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4782): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4782): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4782): Parsing tag category name = system
I/CustomizationCIDLoader( 4782): Parsing tag category name = application
I/CustomizationCIDLoader( 4782): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4782): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4782): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4782): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4782): Parsing tag category name = Settings
D/CustomizationManager( 4782):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4782):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4782): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4782): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4782): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4782): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4782, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=4579
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=4559
I/ActivityManager(  909): Killing 4579:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
I/ActivityManager(  909): Killing 4559:com.android.chrome/u0a96 (adj 15): empty for 1801s
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=4511
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=1413
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 4511:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  909): Killing 1413:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
I/ActivityManager(  909): Recipient 4559
I/ActivityManager(  909): Recipient 4511
D/Process (  909): killProcessQuiet, pid=3871
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Killing 3871:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3871
D/MediaRouterService(  909): Client com.google.android.music (pid 3871): Died!
I/ActivityManager(  909): Recipient 1413
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  909): Skipping PackageSetting{4242f810 com.example.hello/10356} due to missing metadata
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4579
I/acms    ( 1895): Unregistering com.test.thalitest
E/acms    ( 1895): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/dalvikvm-heap( 4168): Grow heap (frag case) to 15.196MB for 1821008-byte allocation
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
D/PMS     (  909): acquireWL(44298328): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1500 10028 null
W/GeofencerStateMachine( 1500): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
D/PMS     (  909): releaseWL(44298328): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
D/PackageBroadcastService( 2256): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4796 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Delaying start of: ServiceRecord{4418a560 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4811 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4796): install
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2256): CP2 sync disabled
I/MultiDex( 4796): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2256, uid=10028, userID:0
I/MultiDex( 4796): loading existing secondary dex files
I/MultiDex( 4796): load found 1 secondary dex files
I/MultiDex( 4796): install done
D/PMS     (  909): acquireWL(426c49c8): PARTIAL_WAKE_LOCK  Icing 0x1 2256 10028 null
I/Icing   ( 2256): doRemovePackageData com.test.thalitest
D/PMS     (  909): releaseWL(426c49c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4796): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4811): install
I/MultiDex( 4811): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4811): loading existing secondary dex files
I/MultiDex( 4811): load found 1 secondary dex files
I/MultiDex( 4811): install done
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4811): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4831 uid=10053 gids={50053, 1023, 3003, 5012}
D/Process (  909): killProcessQuiet, pid=4168
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4168:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
W/FileUtils( 4796): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
W/PackageManager(  909): Unable to load service info ResolveInfo{42208550 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  909): Recipient 4168
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 4796): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4796): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca508b0
E/DriveAsyncService( 4796): disk I/O error (code 3850)
E/DriveAsyncService( 4796): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4796): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4796): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4796): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4796): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4796): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4796): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4796): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PluginProvider( 4831): PluginProvider onCreate
E/SQLiteLog( 4796): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4796): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca508b0
E/DocListDatabase( 4796): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4796): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4796): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4796): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4796): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4796): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4796): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4796): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4796): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4796): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4796): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4796): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4796): threadid=1: thread exiting with uncaught exception (group=0x41876e30)
E/AndroidRuntime( 4796): FATAL EXCEPTION: main
E/AndroidRuntime( 4796): Process: com.google.android.gms.drive, PID: 4796
E/AndroidRuntime( 4796): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4796): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4796): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4796): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4796): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4796): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4796): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4796): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4796): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4796): 	... 10 more
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
E/SQLiteDatabase( 4831): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4831): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4831): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4831): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4831): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4831): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4831): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4831): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4831): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4831): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4831): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4831): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4831): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4831): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4831): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4831): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4831): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4831): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4831): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4831): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4831): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4831): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4831): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4831): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4831): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4831): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4796): killProcess, pid=4796
D/Process ( 4796): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/SQLiteOpenHelper( 4831): Opened registry.db in read-only mode
D/PluginProvider( 4831): current plugin count: 19
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/HtcAppUPService( 4831): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4831): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4831): provider may killed!
W/[PluginManager]RegisterService( 4831): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4831): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4831): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4831): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4831): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4831): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4831): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4831): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4831): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4831): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2898): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Recipient 4796
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4852 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 4796) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteLog( 2898): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2898): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63ad7c10
W/dalvikvm( 2898): threadid=14: thread exiting with uncaught exception (group=0x41876e30)
E/AndroidRuntime( 2898): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2898): Process: com.google.android.googlequicksearchbox:search, PID: 2898
E/AndroidRuntime( 2898): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2898): 	at cid.d(PG:186)
E/AndroidRuntime( 2898): 	at clo.g(PG:594)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2898): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2898): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2898): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2898): 	at clr.tL(PG:827)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2898): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2898): killProcess, pid=2898
D/Process ( 2898): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  909): Client com.google.android.googlequicksearchbox (pid 2898): Died!
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Recipient 2898
I/ActivityManager(  909): Process com.google.android.googlequicksearchbox:search (pid 2898) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10824ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20823ms
E/SQLiteDatabase( 4852): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4852): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4852): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4852): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4852): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4852): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4852): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4852): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4852): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4852): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4852): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4852): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4852): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4852): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4852): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4852): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4852): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4852): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4852): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4852): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4852): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4852): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4852): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4852): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4852): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4852): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4852): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4852): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4852): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4852): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4852): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4852): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4852): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4852): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4852): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4852): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4852): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4852): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4852): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4852): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4852): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4852): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4852): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4852): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4852): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4852): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4852): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4852): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4852): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4852): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4852): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4852): threadid=11: thread exiting with uncaught exception (group=0x41876e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4852): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4852): Process: com.google.android.apps.docs, PID: 4852
E/AndroidRuntime( 4852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4852): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4852): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4852): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4852): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4852): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4852): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 4852): killProcess, pid=4852
D/Process ( 4852): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4868 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4852
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4852) has died.
W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4868): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4868): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4868): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4868): threadid=10: thread exiting with uncaught exception (group=0x41876e30)
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4881 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4868): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4868): Process: com.android.keychain, PID: 4868
E/AndroidRuntime( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4868): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4868): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4868): killProcess, pid=4868
D/Process ( 4868): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450747265874.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 4868
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4868) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20445ms
D/AppTag  ( 4881): getInstance(Context context)
D/AppTag  ( 4881): getInstance(Context context)
D/AppTag  ( 4881): onCreate()
I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4896 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
E/SQLiteDatabase( 4896): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4896): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4896): 	at del.a(PG:264)
E/SQLiteDatabase( 4896): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4896): 	at java.lang.Thread.run(Thread.java:864)
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41d39e70 +
I/Prism.WidgetManager( 1273): onLoadItems() +
E/SQLiteDatabase( 4896): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4896): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4896): 	at del.a(PG:264)
E/SQLiteDatabase( 4896): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4896): 	at java.lang.Thread.run(Thread.java:864)

```
