#### Test 56151093f3290d6_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): acquireWL(41fc9b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(41fc9b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
--------- beginning of /dev/log/main
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 4349): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4349): ====startRecUseTime====
D/htc.customization.log.level( 4349):  is 
W/CustomizationLogLevel( 4349): Level value is invalid, use default level 2
D/CustomizationManager( 4349):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4349): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4349): Parsing tag category name = system
I/CustomizationCIDLoader( 4349): Parsing tag category name = application
I/CustomizationCIDLoader( 4349): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4349): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4349): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4349): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4349): Parsing tag category name = Settings
D/CustomizationManager( 4349):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4349):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 4349): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4349): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4349): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4349): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4349
D/PMS     (  906): acquireHCC(42aa5c28): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42a010c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62775578 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1118680864
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4205f288
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  906): acquireWL(4283a988): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4361 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
W/asset   ( 4361): Copying FileAsset 0x5c7c9390 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4361): Binding Chromium to main looper Looper (main, tid 1) {41fa8568}
I/LibraryLoader( 4361): Expected native library version number "",actual native library version number ""
I/chromium( 4361): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4361): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(429cb418): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4288b5c8:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4361): 1107029440: getState(). Returning 12
D/PMS     (  906): acquireWL(4298db80): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): releaseWL(429cb418): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4361): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4361): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4361): Local Branch: 
I/Adreno-EGL( 4361): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4361): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4361):                  aa63bbd948f41d15fc72f585e
W/chromium( 4361): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4361): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4361): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4361): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4361): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4361): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4361): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4361): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4361): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4361): CordovaWebView is running on device made by: HTC
,W/AwContents( 4361): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1267
W/ResourceType( 4361): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4361): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ff0470, mServedView=org.apache.cordova.engine.SystemWebView{41fb60d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4361): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Enable input method client, pid=4361
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +292ms
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(4283a988): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/PMS     (  906): acquireWL(42ac07e0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  906): releaseWL(42ac07e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/JsMessageQueue( 4361): Set native->JS mode to OnlineEventsBridgeMode
D/PMS     (  906): acquireWL(420684a0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  906): releaseWL(420684a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(42a4d270): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  906): releaseWL(42a4d270): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(43d77bb0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  906): releaseWL(43d77bb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/jxcore_app_log( 4361): JniHelper::setJavaVM(0x41b68010), pthread_self() = 1663839136
D/JX-Cordova( 4361): jxcore cordova android initializing
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 11.960MB for 42652-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 12.042MB for 95956-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 12.118MB for 143930-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 12.232MB for 215890-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 12.408MB for 323830-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 12.679MB for 485740-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 13.658MB for 1092904-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 14.600MB for 1639352-byte allocation
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 15.846MB for 2459024-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42aa5c28): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(42a010c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/dalvikvm-heap( 4361): Grow heap (frag case) to 18.033MB for 3688532-byte allocation
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4409 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42518298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{429821a8: PendingIntentRecord{428436f0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452862893393, Int=60000
,D/PMS     (  906): releaseWL(42518298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4409): SMSBackupAgentService started
,D/SMSBackup( 4409): Checking restore status
D/SMSBackup( 4409): Restore complete
,D/SMSBackup( 4409): cancelCheckAlarm
,D/SMSBackup( 4409): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3391
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3391:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3391
,W/jxcore-log( 4361): Initializing JXcore engine
,W/jxcore-log( 4361): JXcore engine is ready
,W/jxcore-log( 4361): Starting JXcore engine
,W/jxcore-log( 4361): Platform android
W/jxcore-log( 4361): 
,W/jxcore-log( 4361): Process ARCH arm
W/jxcore-log( 4361): 
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42820218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42950930: PendingIntentRecord{42a6b9a0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105836, Int=0
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=65 rxSum=52} preTxRxSum={txSum=63 rxSum=50}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20379 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20380 delay=15s
D/PMS     (  906): releaseWL(42820218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(4298db80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4361): JXcore Cordova bridge is ready!
I/jxcore-log( 4361): 
,W/jxcore-log( 4361): JXcore engine is started
,I/chromium( 4361): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4361): Toggling radios to true
I/jxcore-log( 4361): 
,D/BluetoothAdapter( 4361): enable(): BT is already enabled..!
,D/WifiManager( 4361): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1281
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
D/WifiManager( 4361): disconnect: Base Package Name=com.test.thalitest, uid=10189
,D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4361): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): TDLS: Tear down peers
,I/wpa_supplicant( 1165): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4361): Radios toggled
I/jxcore-log( 4361): 
,I/jxcore-log( 4361): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4361): 
D/WifiService(  906): setWifiEnabled: true pid=4361, uid=10189
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  906): New client listening to asynchronous messages
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1165): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1165): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
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
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/wpa_supplicant( 1165): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): [isWifi] getHotspotEnabled: false,
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8f37bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error -2 - cmd 12
,I/wpa_supplicant( 1165): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1165): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1165): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(4283c650): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): Fast associate: Old scan results
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): State: DISCONNECTED -> SCANNING
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  906):    returned true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20380 mDataStallAlarmIntent=PendingIntent{429e8c78: PendingIntentRecord{42a6b9a0 android broadcastIntent}}
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WISPrService( 3769): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3769): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  906): acquireWL(42ab8ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
D/libc    (  363): [NET] entry_id:6   entry:0xb7822d20  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb782beb0  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb782bd48  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb782bf70  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb782bdf8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb782bc28  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7827468  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb7822af8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(4468a138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43ae1310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1361/10028)
D/WISPrService( 3769): >>>>>WISPrService start isConnected = false<<<<<
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3769): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/PMS     (  906): releaseWL(4468a138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(42ab8ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  906): releaseWL(43ae1310): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3840): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3840/10154)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4468ff38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(4468ff38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1900/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4249/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4249/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2456/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4432 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4432): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4432): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4432): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4432): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4432): Preparing secondary program dexes.
V/DexLibLoader( 4432): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4432): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4432): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4432): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4432): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4432): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4432): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4432): Dex already copied
D/OdexVerifier( 4432): Odex verification is skipped.
,V/DexLibLoader( 4432): Creating class loader
,V/DexLibLoader( 4432): Finished creating class loader
V/DexLibLoader( 4432): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4432): Dex already copied
D/OdexVerifier( 4432): Odex verification is skipped.
,V/DexLibLoader( 4432): Creating class loader,
V/DexLibLoader( 4432): Finished creating class loader,
V/DexLibLoader( 4432): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4432): Dex already copied
D/OdexVerifier( 4432): Odex verification is skipped.
,V/DexLibLoader( 4432): Creating class loader,
V/DexLibLoader( 4432): Finished creating class loader,
V/DexLibLoader( 4432): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4432): Dex already copied
D/OdexVerifier( 4432): Odex verification is skipped.
,V/DexLibLoader( 4432): Creating class loader
,V/DexLibLoader( 4432): Finished creating class loader
,V/DexLibLoader( 4432): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4432): DexLibLoader.ensureDexLoaded took 19 ms
,I/SensorManager(  906): mEventCount = 900
,W/dalvikvm( 4432): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4432): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-72
I/wpa_supplicant( 1165): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
I/wpa_supplicant( 1165): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-89
D/wpa_supplicant( 1165): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1165): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1165): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1165): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1165): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1165): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-49
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->w,pa_state is 3
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 1
I/wpa_supplicant( 1165): wpa_s->is_screen_on 1
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): selected network = 2
D/wpa_supplicant( 1165): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8f394e8  current_ssid=0x0
D/wpa_supplicant( 1165): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1165): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1165): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1165): check if in concurrent case
,I/wpa_supplicant( 1165): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1165): RSN: PMKSA cache search - network_ctx=0xb8f394e8 try_opportunistic=0
D/wpa_supplicant( 1165): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1165): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1165): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1165): nl80211: Unsubscribe mgmt frames handle 0xb8f38718 (mode change)
D/wpa_supplicant( 1165): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8f38718
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb8f38718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Connect (ifindex=22)
,D/wpa_supplicant( 1165):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165):   * freq=2412
D/wpa_supplicant( 1165):   * Auth Type 0
D/wpa_supplicant( 1165):   * WPA Versions 0x2
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1165): nl80211: Connect request send successfully
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (910) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-48
I/wpa_supplicant( 1165): tsf=0000000108571305
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-50
I/wpa_supplicant( 1165): tsf=0000000108571317
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-49
I/wpa_supplicant( 1165): tsf=0000000108571321
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2452
I/wpa_supplicant( 1165): level=-72
I/wpa_supplicant( 1165): tsf=0000000022381042
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000000022381046
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-89
I/wpa_supplicant( 1165): tsf=0000000108571328
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC4688432
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-89
I/wpa_supplicant( 1165): tsf=0000000108571332
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1165): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108571305, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 108571317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 2412, timestamp: 108571321, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2452, timestamp: 22381042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -83, frequency: 2437, timestamp: 22381046, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+,TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 108571328, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -89, frequency: 2462, timestamp: 108571332, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4432): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1165): nl80211: Connect event
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1165): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): TDLS: Remove peers on association
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1165): EAPOL: enable timer tick
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1165): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1165): Get randomness: len=32 entropy=7
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiS,sid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8f389f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  906): updateConnectedAP...
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f05b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1165): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1165): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1165): set send_ind_to_ndc = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1165): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1165): EAPOL authentication completed successfully
I/wpa_supplicant( 1165): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 79,
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3769): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WISPrService( 3769): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 1
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42dbd750): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a1b0e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a1b0e0 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4432): Verify
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4432): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4432): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4186
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4186:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(4462d390): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,D/PMS     (  906): acquireWL(4471a6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
,D/PMS     (  906): releaseWL(4462d390): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/GCM     ( 1361): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
D/PMS     (  906): releaseWL(4471a6c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  906): Recipient 4186
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4462 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): service - onCreate()
,D/AutoSetting( 1398): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  906): request 425b33b8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4432): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4432): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4432): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4462): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4462): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4462): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4462): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4478 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4462/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4462/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4462/10078)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4432): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4495 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3823
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 4432): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4432): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4432): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4432): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/ActivityManager(  906): Killing 3823:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/dalvikvm( 4432): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4432): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4432): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4432): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4432): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4432): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4495): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm-heap( 4432): Grow heap (frag case) to 9.971MB for 84664-byte allocation
W/dalvikvm( 4432): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4432): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4432): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4432): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4432): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4432): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4432): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4495): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4495): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4495): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4495): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 9.983MB for 28144-byte allocation
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 10.025MB for 39954-byte allocation
I/ActivityManager(  906): Recipient 3823
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 10.100MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4495/10151)
,V/WebViewChromiumFactoryProvider( 4495): Binding Chromium to main looper Looper (main, tid 1) {41fae028}
,I/LibraryLoader( 4495): Expected native library version number "",actual native library version number ""
,I/chromium( 4495): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4495): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(42a066f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  906): acquireWL(42a56dc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4495): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(42a066f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4495): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4495): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4495): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4495): Local Branch: 
I/Adreno-EGL( 4495): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4495): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4495):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4495): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4495/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4495/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
,D/Process (  906): killProcessQuiet, pid=3951
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3951:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4432): Grow heap (frag case) to 10.288MB for 75760-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441f1e70 u0 ReceiverList{441f1e30 4432 com.facebook.katana/10026/u0 remote:441d2120}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441f1e70 u0 ReceiverList{441f1e30 4432 com.facebook.katana/10026/u0 remote:441d2120}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{446d9588 u0 ReceiverList{446d5af8 4432 com.facebook.katana/10026/u0 remote:446d5398}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/PMS     (  906): acquireWL(43b7d720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1416 10028 null
,D/PMS     (  906): releaseWL(43b7d720): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 3951
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1416): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(42ade070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1416 10028 null
D/PMS     (  906): releaseWL(42ade070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4432): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4432): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1165): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1165): EAPOL: disable timer tick
,I/Choreographer( 4361): Skipped 237 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4361): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
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
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP,
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(42dbd750): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!,
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20382 delay=15s
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 3769): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@428dc340
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(442932f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4462/10078)
,D/PMS     (  906): acquireWL(438284d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43ac2618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  906): releaseWL(442932f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4262c908
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
D/PMS     (  906): releaseWL(438284d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4262c908, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42711488
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@427d5720
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,W/PMS     (  906): mWirelessDisplayManager is null
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/CheckinService( 1230): Preparing to send checkin request
I/EventLogService( 1230): Accumulating logs since 1452862842586
,I/GoogleHttpClient( 1230): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1230): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1230): awaiting user notification for token
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ff5d88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 7 3 12
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 377ms
D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
,I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1255): applyRouting -2
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4361
D/PMS     (  906): acquireWL(43283438): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,D/PMS     (  906): releaseWL(43283438): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/ResourceType( 4361): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4361): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41fb60d8 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427fd568)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(42800be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42800be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2456): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2456): [MTP][onReceive]-
D/HtcPowerSaver(  906): updateBatteryInfo
D/AlarmManager(  906): ACTION_SCREEN_ON
D/NfcService( 1255): applyRouting - 0
,D/AutoSetting( 1398): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1255): applyRouting -2
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(424fe4e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  906): releaseWL(424fe4e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4577 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/TetherSettings( 3769): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3769): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3769): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3769): Cust_ConnectToPC   : spcsc>false
D/        ( 3769): Cust_ConnectToPC   : IPT>true
D/        ( 3769): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3769): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3769): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3769): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3769): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3769): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1114): stop update clock
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 3769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3769): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3769): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3769):  defaultType:0
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20383 delay=15s
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4577): install
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
I/MultiDex( 4577): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,I/MultiDex( 4577): loading existing secondary dex files
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,I/MultiDex( 4577): load found 1 secondary dex files
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4590 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/NetworkPolicy(  906): updateScreenOn: false
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
,I/MultiDex( 4577): install done
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4577): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(428ba8e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4590 1000 null
D/PMS     (  906): acquireWL(441226e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1416 10028 null
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): onScreenOn: 1452862899966
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1811): onScreenOn: 1452862899967
,D/PMS     (  906): releaseWL(441226e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42711488
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42711488, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@427d5720
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(429c6c88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/PMS     (  906): releaseWL(428ba8e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): releaseWL(429c6c88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/SmartSyncUtils( 4590): getMobilePolicyEnabled, result = true
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20383 mDataStallAlarmIntent=PendingIntent{42868968: PendingIntentRecord{42a6b9a0 android broadcastIntent}}
,D/Process (  906): killProcessQuiet, pid=4219
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 4219:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  906): acquireWL(44160e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
I/ActivityManager(  906): Recipient 4219
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/NetworkPolicy(  906): updateScreenOn: false
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4590): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): releaseWL(4283c650): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(44160e40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427d5720
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427d5720, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427d5720, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427d5720
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275b420 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4275b420 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1900): Checking Certificates
I/acms    ( 1900): Checking Developer Certificates
I/acms    ( 1900): Checking Application Certificates
I/acms    ( 1900): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1900): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1900): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1900): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1900): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1900): Updating next query delay: 75600000
I/mlserverapp( 1900): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1900): cancelACMSProgrammedChecks
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1900/1000)
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/NetworkMonitor( 3840): type=WIFI subType= reason=null isConnected=true
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4462/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3863/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4249/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3840/10154)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/PMS     (  906): acquireWL(4424e518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4249/10100)
D/PMS     (  906): acquireWL(4471bab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2456/10021)
,D/PMS     (  906): acquireWL(436e7b58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  906): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4619 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  906): releaseWL(4471bab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(4424e518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] getTotalRam: 1873 Mb
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4465ce28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1416 10028 null
D/PMS     (  906): releaseWL(4465ce28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1811): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1811): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1811): onScreenOff
D/PMS     (  906): acquireWL(43ac76f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,D/PMS     (  906): releaseWL(43ac76f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/AutoSetting( 1398): service - mHandler: cancel location update
D/AutoSetting( 1398): service -           changes count: 0
,D/GCM     ( 1361): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4cfd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(42bed6e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4462): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4462): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1398): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1398): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4495/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1853/10178)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 285
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4095): Grow heap (frag case) to 13.525MB for 1821008-byte allocation
,W/fb4a(:<default>):UserScope( 4432): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4432): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=100 [1][1][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,I/Adreno-EGL( 4577): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4577): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4577): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4577): Local Branch: 
I/Adreno-EGL( 4577): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4577): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4577):                  aa63bbd948f41d15fc72f585e
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  906): acquireWL(42a829b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  906): releaseWL(42a829b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4619): LocationClient connecting
,I/Adreno-EGL( 4577): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4577): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4577): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4577): Local Branch: 
I/Adreno-EGL( 4577): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4577): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4577):                  aa63bbd948f41d15fc72f585e
,I/NewsWeather( 4619): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4619): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4619): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4619): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4619): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,E/fb4a(:<default>):LocalFbBroadcastManager( 4432): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4577/10028)
,D/GCM     ( 1361): Connected
D/PMS     (  906): acquireWL(43c47650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  906): releaseWL(42bed6e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  906): releaseWL(43c47650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4433ad08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
,I/ProviderInstaller( 4619): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1361): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43ce2860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4433ad08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(43ce2860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(43b71058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
I/NewsWeather( 4619): Last usage 0, idle 1452862900s, sync interval 2592000s
,I/NewsWeather( 4619): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4619): onConnected null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/PMS     (  906): releaseWL(43b71058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/PMS     (  906): acquireWL(436646a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1416 10028 null
,W/GCoreFlp( 1416): No location to return for getLastLocation()
,I/NewsWeather( 4619): LocationClient onConnected: location null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/PMS     (  906): acquireWL(425b3700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1416 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/PMS     (  906): releaseWL(436646a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/PMS     (  906): releaseWL(425b3700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4432/10026)
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4619): [NET] getaddrinfo-,err=8
D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4619): [NET] getaddrinfo-, 1
,D/libc    ( 4619): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{422b5610 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  363): [NET] +++++ res_nsend xid =5d76 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 9 2 12
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  363): [NET]res_nsend:resplen=70
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4619): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4619): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(42a56dc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/Settings( 4577): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  906): acquireWL(446c2430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(446c2430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(432b6068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68368, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  906): killProcessQuiet, pid=4249
D/PMS     (  906): releaseWL(436e7b58): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,I/ActivityManager(  906): Killing 4249:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(432b6068): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c7e2b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/PMS     (  906): releaseWL(43c7e2b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  906): Recipient 4249
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=14 [14][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4577): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4577): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4577): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4577): Local Branch: 
I/Adreno-EGL( 4577): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4577): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4577):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1230): Sending checkin request (9009 bytes)
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
,D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ab17 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7c6a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/PMS     (  906): acquireWL(44addad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  906): releaseWL(44addad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=22 [18][4][0]
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1230): awaiting user notification for token
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{4236fa90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 9 4 12
,I/CheckinTask( 1230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1230): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(43ac2618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1230): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4226a550 that was originally bound here
E/ActivityThread( 1230): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4226a550 that was originally bound here
E/ActivityThread( 1230): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1230): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1230): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1230): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1230): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1230): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1230): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1230): 	at bks.a(SourceFile:298)
E/ActivityThread( 1230): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1230): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1230): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1361): GCM config loaded
,D/AutoSetting( 1489): service - handleMessage() stop self
,D/AutoSetting( 1489): service - onDestroy() END
,D/AutoSetting( 1489): service - handleMessage() quit looper
,I/GAV2    ( 4495): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4265
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 4265:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4265
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV4    ( 4619): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4289
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4289:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4289
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43ae0f40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(42be3fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=131571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42be3fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b29f68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): acquireWL(42b1b490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=132140, Int=0
D/PMS     (  906): releaseWL(42b1b490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b06ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42b29f68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42b06ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42930218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42930218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1398): service - mHandler: update timezone
,D/AutoSetting( 1398): service - handleMessage() stop self
,D/AutoSetting( 1398): service - handleMessage() quit looper
,D/AutoSetting( 1398): service - onDestroy() END
,D/AutoSetting( 1489): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1489): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1489): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1489): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1489): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: Full, plugged
,D/DotMatrix( 1574): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1489): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1489): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1489): service - mHandler: update timezone
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1489): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1489): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1489): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1489): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{42393458 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  906): acquireWL(42553af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42553af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  906): killProcessQuiet, pid=3863
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3863:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3863
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43ac4820 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(429c0190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{42a5b6c0: PendingIntentRecord{429a03f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141748, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{428b74c8: PendingIntentRecord{429b5db8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141952, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=162159, Int=0
D/PMS     (  906): acquireWL(42aaee48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  906): acquireWL(42a5ad90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): acquireWL(42a5adc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(429c0190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(42aaee48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(429ec808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=30 [13][4][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  363): [NET] +++++ res_nsend xid =d362 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(42aa3c40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(42a5adc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(429ec808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42aad408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42aad408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4619): Last usage 0, idle 1452862950s, sync interval 2592000s
,I/NewsWeather( 4619): setPeriodicSync in seconds 2592000,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{4203b990 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 3 12 4 12
,D/PMS     (  906): acquireWL(442ee180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  906): releaseWL(442ee180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42a89480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 112546, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(42aa3c40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  906): releaseWL(42a89480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/PMS     (  906): acquireWL(43a35b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43a35b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(42a5ad90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1489): service - handleMessage() stop self
,D/AutoSetting( 1489): service - onDestroy() END
,D/AutoSetting( 1489): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4307
,I/ActivityManager(  906): Killing 4307:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4307
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(432ba108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=191571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432ba108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436822f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=192265, Int=0
,D/PMS     (  906): acquireWL(42a6dda8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(436822f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42873210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42a6dda8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42873210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42c0a6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c0a6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
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
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(44300110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=224467, Int=0
,D/PMS     (  906): acquireWL(447259f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44300110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4471eec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=5 [35][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(44303ca0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(447259f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4471eec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43b5e8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43b5e8c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4619): Last usage 0, idle 1452863013s, sync interval 2592000s
I/NewsWeather( 4619): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{4213b5d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 12 3 12
,D/PMS     (  906): acquireWL(43fb3618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(43fb3618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ded4d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 162620, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/PMS     (  906): releaseWL(44303ca0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  906): releaseWL(42ded4d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(442f2130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): releaseWL(442f2130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(441b7c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4277eeb8: PendingIntentRecord{4297d1a8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229537, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4681 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{428fbaa0: PendingIntentRecord{42a137b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452863009496, Int=10800000
,D/PMS     (  906): releaseWL(441b7c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4681/10047)
,D/Process (  906): killProcessQuiet, pid=4236
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4236:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4236
,D/PMS     (  906): acquireWL(44304048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4292a2f8: PendingIntentRecord{43a4dc50 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231271, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{4464eb28: PendingIntentRecord{4297d1a8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231573, Int=0
,D/PMS     (  906): releaseWL(44304048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4471c1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=251571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4471c1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43da7300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43da7300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4390d358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=254535, Int=0
,D/PMS     (  906): acquireWL(442bab18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(4390d358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4296e0e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(442bab18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4296e0e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(442f0410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(442f0410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43d89c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=311571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d89c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42fc5948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fc5948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(44298738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=348730, Int=0
,D/PMS     (  906): acquireWL(44698388): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(44298738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43a4d168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=4 [23][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4364e6e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(44698388): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43a4d168): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4469da90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4469da90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4619): Last usage 0, idle 1452863137s, sync interval 2592000s
,I/NewsWeather( 4619): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41fd4970 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 3 20 3 12
,D/PMS     (  906): acquireWL(42ac9970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(42ac9970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(446dbc08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 225034, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(4364e6e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
,D/PMS     (  906): releaseWL(446dbc08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(44183980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44183980): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1361): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1361): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1361): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1361): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1361): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1361): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1361): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1361): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 4059): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4059): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4059): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4059): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4059): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4059): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4059): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4059): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{42127788 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 10 3 12
,D/libc    ( 4059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4059): [NET] getaddrinfo-,err=8
D/libc    ( 4059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4059): [NET] getaddrinfo-, 1
,D/libc    ( 4059): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =65b3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4059): [NET] getaddrinfo_proxy-, success
,I/global  ( 4059): call createSocket() return a new socket.
D/libc    ( 4059): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4059): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4059): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(446802f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=371571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(446802f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e0e188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e0e188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(442926c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=378795, Int=0
,D/PMS     (  906): acquireWL(44286690): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(442926c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(436638d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44286690): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(436638d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(432c4538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=431571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432c4538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b826f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b826f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43d5e770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=491571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d5e770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44314810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44314810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  403): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43619d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=551571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43619d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a8b498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42a8b498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3769): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3769): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3769): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3769): Cust_ConnectToPC   : spcsc>false
D/        ( 3769): Cust_ConnectToPC   : IPT>true
,D/        ( 3769): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3769): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3769): Index of the first 1 = 3
W/Settings( 3769): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3769): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3769): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3769): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3769): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3769): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3769): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43609ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43609ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4360b7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{44228058: PendingIntentRecord{43a4dc50 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531579, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=596629, Int=0
,D/PMS     (  906): acquireWL(42aaf4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4360b7e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(436534a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=2 [38][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): acquireWL(44720320): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42aaf4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(436534a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4619): Last usage 0, idle 1452863385s, sync interval 2592000s
,I/NewsWeather( 4619): setPeriodicSync in seconds 2592000
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42888fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42888fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{42378668 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 19 5 12
D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4619): [NET] getaddrinfo-,err=8
D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4619): [NET] getaddrinfo-, 1
,D/libc    ( 4619): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b421 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4619): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4619): [NET] getaddrinfo-,err=8,
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(43b6f480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43b61568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43b6f480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 349237, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(44720320): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
,W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(43b61568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(432b07b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(432b07b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(429c0e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=611571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429c0e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429ad820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(429ad820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4286c218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4286c218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  906): acquireWL(4281c2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=626715, Int=0
,D/PMS     (  906): acquireWL(427fd7b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(4281c2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42569ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(427fd7b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42569ea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42b09760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=671571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b09760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429b74e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429b74e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42816dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42816dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/Process (  906): killProcessQuiet, pid=4322
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4322:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4322
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(429273a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=731571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429273a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424dcee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(424dcee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42af19e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42af19e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42fc1b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{42268710: PendingIntentRecord{428e6af8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785814, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{430b25b8: PendingIntentRecord{42a58d30 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452863150079, Int=1800000
,D/PMS     (  906): acquireWL(43641eb0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1230 10028 null
,D/PMS     (  906): releaseWL(42fc1b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(42a535e0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1230 10028 null
,D/PMS     (  906): releaseWL(43641eb0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1230): Aggregate from 1452862899275 (log), 1452861350021 (data)
,D/PMS     (  906): releaseWL(42a535e0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  906): acquireWL(441efab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=791571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441efab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43d07048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43d07048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ae7320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ae7320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a827b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=851571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a827b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4295cf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4295cf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a6d4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42a6d4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42aa5868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=911571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42aa5868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43d748d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43d748d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(435688a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435688a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43d77ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=971571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d77ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4355ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4355ce30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b67150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43b67150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a50310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{429a9ce8: PendingIntentRecord{42843588 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452863729686, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{429420a0: PendingIntentRecord{42efe350 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452863800057, Int=0
,W/ContextImpl( 4590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4590): call getInstance()
,D/SmartSyncUtils( 4590): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4590): MY_DEBUG = false
D/PMS     (  906): releaseWL(42a50310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(429f1940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4590 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4590): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4590): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4590): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4590): SettingOnTime = 1452924000000, randomSettingOnTime = 1452923384000
,D/SmartSyncScreenOnOffTimeReceiver( 4590): SettingOffTime = 1452902400000, randomSettingOffTime = 1452907109000
,D/SmartSyncScreenOnOffTimeReceiver( 4590): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4590): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4590): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(429f1940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(438cbcb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1031571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438cbcb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a00ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42a00ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44d420e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(44d420e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4433d9f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1091571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4433d9f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44324d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{42ff16c0: PendingIntentRecord{429a0a38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012113, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1091979, Int=0
,D/PMS     (  906): acquireWL(44320e58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10028 null
,D/PMS     (  906): releaseWL(44320e58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(44302328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  906): acquireWL(443021a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44324d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(44302328): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(442f4788): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [48][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(442e3d58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1361): Message class mow
D/PMS     (  906): acquireWL(441200b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
D/PMS     (  906): releaseWL(443021a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(442e3d58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  906): acquireWL(43d122f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/NewsWeather( 4619): Last usage 0, idle 1452863880s, sync interval 2592000s
,I/NewsWeather( 4619): setPeriodicSync in seconds 2592000
D/PMS     (  906): releaseWL(43d122f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): acquireWL(43ae3068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  906): releaseWL(442f4788): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(43ae3068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4619): Skip sync for lookup editions
,I/NewsWeather( 4619): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4619): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{424bc0a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4619): Unrecoverable authentication exception
E/NewsWeather( 4619): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4619): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4619): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1114): com.google.android.gms 5 12 3 12
,D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4619): [NET] getaddrinfo-,err=8
D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    ( 4619): [NET] getaddrinfo-, 1
,D/libc    ( 4619): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =245a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4619): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4619): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4619): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(432adef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(432adef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42be3fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  906): releaseWL(42be3fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4619): Failed to syncNewsAppData
,E/NewsWeather( 4619): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b1dc80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): releaseWL(441200b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 597195, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42b1dc80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1416/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42a10e58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42a10e58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1328): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(4297e8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4297e8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ae11e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42217180: PendingIntentRecord{4294ebd8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1122082, Int=0
,D/PMS     (  906): acquireWL(430bcb68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43ae11e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4271fa80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(430bcb68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4271fa80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(43611f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1151571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43611f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b0b450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b0b450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43619ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43619ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43641b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1211571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43641b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42aaefa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42aaefa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42af4238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1271571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42af4238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429881b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(429881b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a0d690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42a0d690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(429a7f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1331571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429a7f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42823fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42823fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4364ed10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4364ed10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43664f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1391571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43664f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a182e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(42a182e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a63718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42a63718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423c7628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1451571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423c7628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b6d0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b6d0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42fc1ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42fc1ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42514930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{42268710: PendingIntentRecord{428e6af8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505844, Int=0
,D/PMS     (  906): releaseWL(42514930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(430bda20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1511571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430bda20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4428f050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4428f050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42a53568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42a53568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43d767f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1571571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d767f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44717808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44717808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429f04b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(429f04b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42bb6ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1631571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42bb6ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44318ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PMS     (  906): releaseWL(44318ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4328b2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1691571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4328b2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429dc3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429dc3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bcbd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bcbd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bc7860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1751571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc7860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4471acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  906): releaseWL(4471acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4288bb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4288bb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42a58260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1811571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a58260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(432915d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(432915d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42ad4600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(42ad4600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  906): Prepared write state in 45ms
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-27-00.bin
,D/PMS     (  906): acquireWL(43b127e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4285cfc8: PendingIntentRecord{4285c338 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1871571, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b127e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425b3760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(425b3760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4328b958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4328b958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4762): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4762): ====startRecUseTime====
D/htc.customization.log.level( 4762):  is 
W/CustomizationLogLevel( 4762): Level value is invalid, use default level 2
D/CustomizationManager( 4762):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4762): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4762): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4762): Parsing tag category name = system
I/CustomizationCIDLoader( 4762): Parsing tag category name = application
I/CustomizationCIDLoader( 4762): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4762): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4762): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4762): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4762): Parsing tag category name = Settings
D/CustomizationManager( 4762):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4762):  All configurations done spent 0.161 (s)
W/HtcNativeFlag( 4762): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4762): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4762): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4762): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4762, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4361
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4361:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=4495
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4478
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4462
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=1398
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4495:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4478:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4462:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 1398:com.htc.sense.hsp/u0a53 (adj 15): empty for 1802s
D/Process (  906): killProcessQuiet, pid=3840
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4409
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4059
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  906): Copying FileAsset 0x62be1f28 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Killing 3840:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4409:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  906): Killing 4059:com.android.vending/u0a73 (adj 15): empty for 1824s
I/ActivityManager(  906):   Force finishing activity ActivityRecord{424d45d0 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  906): Recipient 4462
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4409
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 1398
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4478
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4495
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  906): Recipient 4059
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4361 uid 10189
D/DotMatrix( 1574): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1574): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/dalvikvm-heap( 4095): Grow heap (frag case) to 15.222MB for 1821008-byte allocation
E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  906): Recipient 3840
W/BroadcastQueue(  906): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  906): android.os.DeadObjectException
W/BroadcastQueue(  906): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  906): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  906): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/MediaRouterService(  906): Client com.google.android.music (pid 3840): Died!
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
I/acms    ( 1900): Unregistering com.test.thalitest
E/acms    ( 1900): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1416): Ignoring removeGeofence because network location is disabled.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(44208c78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1416 10028 null
D/PMS     (  906): releaseWL(44208c78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/WindowState(  906): WIN DEATH: Window{42a34778 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1295): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PackageBroadcastService( 1230): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4777 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  906): Delaying start of: ServiceRecord{44720750 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/MultiDex( 4777): install
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4777): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/MultiDex( 4777): loading existing secondary dex files
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4777): load found 1 secondary dex files
I/MultiDex( 4777): install done
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4793 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 1230): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1230, uid=10028, userID:0
D/PMS     (  906): acquireWL(44301ea0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
I/Icing   ( 1230): doRemovePackageData com.test.thalitest
D/PMS     (  906): releaseWL(44301ea0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4777): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4793): install
I/MultiDex( 4793): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4793): loading existing secondary dex files
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4793): load found 1 secondary dex files
I/MultiDex( 4793): install done
I/ProviderInstaller( 4793): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4811 uid=10053 gids={50053, 1023, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=4095
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4095:com.google.android.apps.plus/u0a160 (adj 15): empty for 1803s
E/SQLiteLog( 4777): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4777): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c95f860
E/DriveAsyncService( 4777): disk I/O error (code 3850)
E/DriveAsyncService( 4777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4777): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4777): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4777): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4777): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4777): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4777): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4777): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4777): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4777): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c95f860
I/ActivityManager(  906): Recipient 4095
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/DocListDatabase( 4777): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4777): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4777): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4777): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4777): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4777): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4777): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4777): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4777): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4777): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4777): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4777): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4777): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4777): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4777): threadid=1: thread exiting with uncaught exception (group=0x41b79e30)
E/AndroidRuntime( 4777): FATAL EXCEPTION: main
E/AndroidRuntime( 4777): Process: com.google.android.gms.drive, PID: 4777
E/AndroidRuntime( 4777): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4777): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4777): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4777): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4777): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4777): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4777): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4777): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4777): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4777): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4777): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4777): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4777): 	... 10 more
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4777): killProcess, pid=4777
D/Process ( 4777): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/PluginProvider( 4811): PluginProvider onCreate
E/SQLiteDatabase( 4811): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4811): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4811): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4811): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4811): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4811): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4811): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4811): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4811): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4811): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4811): Opened registry.db in read-only mode
D/PluginProvider( 4811): current plugin count: 19
D/HtcAppUPService( 4811): HtcUPDataProvider onCreate()
W/PackageManager(  906): Unable to load service info ResolveInfo{428fb258 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/[PluginManager]RegisterService( 4811): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4811): provider may killed!
W/[PluginManager]RegisterService( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4811): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4811): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4811): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4811): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4811): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4811): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4811): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Recipient 4777
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4832 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4777) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4832, uid=10073, userID:0
D/Finsky  ( 4832): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4832/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4832/10073)
D/Finsky  ( 4832): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4832): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4832): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4832): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4832): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4832): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4832): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4832): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4832): threadid=25: thread exiting with uncaught exception (group=0x41b79e30)
E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 4832): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4832): Process: com.android.vending, PID: 4832
E/AndroidRuntime( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4832): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4832): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4832): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4832): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4832, uid=10073, userID:0
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4832): killProcess, pid=4832
D/Process ( 4832): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2908): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Recipient 4832
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.vending (pid 4832) has died.
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4865 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2908): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2908): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5d763bb8
W/dalvikvm( 2908): threadid=14: thread exiting with uncaught exception (group=0x41b79e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2908): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2908): Process: com.google.android.googlequicksearchbox:search, PID: 2908
E/AndroidRuntime( 2908): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2908): 	at cid.d(PG:186)
E/AndroidRuntime( 2908): 	at clo.g(PG:594)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2908): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2908): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2908): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2908): 	at clr.tL(PG:827)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2908): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2908): killProcess, pid=2908
D/Process ( 2908): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 2908
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2908): Died!
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2908) has died.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10611ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20611ms
E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4865): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4865): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4865): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4865): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4865): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4865): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4865): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4865): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4865): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4865): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4865): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4865): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4865): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4865): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4865): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4865): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4865): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4865): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4865): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4865): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4865): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4865): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4865): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4865): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4865): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4865): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4865): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4865): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4865): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4865): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4865): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4865): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4865): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4865): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4865): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4865): threadid=11: thread exiting with uncaught exception (group=0x41b79e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4865): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4865): Process: com.google.android.apps.docs, PID: 4865
E/AndroidRuntime( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4865): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4865): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4865): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4865): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4865): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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

```
