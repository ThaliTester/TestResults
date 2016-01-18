#### Test 56151093f6e24ff_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  903): acquireWL(41e33d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(41e33d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of /dev/log/main
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,E/cutils-trace( 4428): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4428): ====startRecUseTime====
D/htc.customization.log.level( 4428):  is 
W/CustomizationLogLevel( 4428): Level value is invalid, use default level 2
D/PMS     (  903): acquireWL(423461a0): PARTIAL_WAKE_LOCK  Icing 0x1 2219 10028 null
D/PMS     (  903): releaseWL(423461a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(420993c8): PARTIAL_WAKE_LOCK  Icing 0x1 2219 10028 null
D/PMS     (  903): releaseWL(420993c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  903): acquireWL(424ae140): PARTIAL_WAKE_LOCK  Icing 0x1 2219 10028 null
D/PMS     (  903): releaseWL(424ae140): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  903): acquireWL(420a2f70): PARTIAL_WAKE_LOCK  Icing 0x1 2219 10028 null
D/CustomizationManager( 4428):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4428): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4428): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4428): Parsing tag category name = system
I/CustomizationCIDLoader( 4428): Parsing tag category name = application
I/CustomizationCIDLoader( 4428): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4428): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4428): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4428): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4428): Parsing tag category name = Settings
D/CustomizationManager( 4428):  Read CID file spent 0.115 (s)
D/CustomizationManager( 4428):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 4428): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4428): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4428): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4428): Fail to get flag for type 'language', use default value: -1
D/PMS     (  903): releaseWL(420a2f70): PARTIAL_WAKE_LOCK  Icing 0x1 null
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4428
D/PMS     (  903): acquireHCC(433d94d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42602900): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x62e29340 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1137832224
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c4f070
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/PMS     (  903): acquireWL(423d1e00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4443 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4443): Copying FileAsset 0x5c758428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4443): Binding Chromium to main looper Looper (main, tid 1) {41ae2868}
I/LibraryLoader( 4443): Expected native library version number "",actual native library version number ""
I/chromium( 4443): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4443): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4412bd78:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4443): 1102021264: getState(). Returning 12
D/PMS     (  903): acquireWL(425650a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(4233df50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(425650a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4443): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4443): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4443): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4443): Local Branch: 
I/Adreno-EGL( 4443): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4443): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4443):                  aa63bbd948f41d15fc72f585e
W/chromium( 4443): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4443): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4443): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4443): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4443): CordovaWebView is running on device made by: HTC
,W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1268
,W/ResourceType( 4443): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b29980, mServedView=org.apache.cordova.engine.SystemWebView{41aef5a8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  903): Enable input method client, pid=4443
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +297ms
W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
,D/PMS     (  903): releaseWL(423d1e00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4443): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4443): JniHelper::setJavaVM(0x415b8048), pthread_self() = 1663640072
,D/JX-Cordova( 4443): jxcore cordova android initializing
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4487 uid=10077 gids={50077}
D/PMS     (  903): acquireWL(42655808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{423b1ab0: PendingIntentRecord{4212ca68 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453125223572, Int=60000
,D/PMS     (  903): releaseWL(42655808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4487): SMSBackupAgentService started
,D/SMSBackup( 4487): Checking restore status
D/SMSBackup( 4487): Restore complete
,D/SMSBackup( 4487): cancelCheckAlarm
,D/SMSBackup( 4487): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=4219
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4219:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4219
,D/PMS     (  903): acquireWL(425782a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
,D/PMS     (  903): acquireWL(424d1e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
,D/PMS     (  903): releaseWL(425782a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(424d1e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1114): WifiActivity: 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.070MB for 95956-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.150MB for 143930-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.265MB for 215890-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 13.709MB for 1092904-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 15.937MB for 2459024-byte allocation
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(433d94d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42602900): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 18.066MB for 3688532-byte allocation
,W/jxcore-log( 4443): Initializing JXcore engine
,W/jxcore-log( 4443): JXcore engine is ready
,W/jxcore-log( 4443): Starting JXcore engine
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=155 rxSum=143} preTxRxSum={txSum=152 rxSum=141}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19390 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19391 delay=15s
D/PMS     (  903): acquireWL(4239cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41ca9458: PendingIntentRecord{42597aa0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105389, Int=0
D/PMS     (  903): releaseWL(4239cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/jxcore-log( 4443): Platform android
W/jxcore-log( 4443): 
,W/jxcore-log( 4443): Process ARCH arm
W/jxcore-log( 4443): 
,D/PMS     (  903): releaseWL(4233df50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4443): JXcore Cordova bridge is ready!
I/jxcore-log( 4443): 
,W/jxcore-log( 4443): JXcore engine is started
,I/chromium( 4443): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4443): Toggling radios to true
I/jxcore-log( 4443): 
,D/BluetoothAdapter( 4443): enable(): BT is already enabled..!
,D/WifiManager( 4443): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1342
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
D/WifiManager( 4443): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
,D/WifiManager( 4443): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
,I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3),
,I/jxcore-log( 4443): Radios toggled
I/jxcore-log( 4443): 
D/WifiService(  903): New client listening to asynchronous messages
,D/WifiService(  903): setWifiEnabled: true pid=4443, uid=10189
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 4443): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4443): 
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48,
,I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412,
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
,D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8a78bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  903): release()
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(42465168): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19391 mDataStallAlarmIntent=PendingIntent{43e31668: PendingIntentRecord{42597aa0 android broadcastIntent}}
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false,
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  903): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4188): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  903): New client listening to asynchronous messages
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4188): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4188): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] entry_id:6   entry:0xb8bc5fc8  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb8bc6538  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb8bc6368  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8bc6180  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb8bca028  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8bca2d8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8bca108  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb8bc6720  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8bca1d0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8bca410  removed 
D/libc    (  364): [NET] entry_id:11   entry:0xb8bc68f8  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4188): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/PMS     (  903): acquireWL(42f31848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/PMS     (  903): acquireWL(424496e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  903): releaseWL(424496e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  903): acquireWL(4411cec0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1366/10028)
D/PMS     (  903): releaseWL(42f31848): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  903): releaseWL(4411cec0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3907): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43da7fc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
D/PMS     (  903): releaseWL(43da7fc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3907/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1872/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2477/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4511 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4511): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4511): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4511): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4511): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4511): Preparing secondary program dexes.
V/DexLibLoader( 4511): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4511): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4511): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4511): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4511): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4511): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4511): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4511): Dex already copied
D/OdexVerifier( 4511): Odex verification is skipped.
,V/DexLibLoader( 4511): Creating class loader
,V/DexLibLoader( 4511): Finished creating class loader
V/DexLibLoader( 4511): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4511): Dex already copied
D/OdexVerifier( 4511): Odex verification is skipped.
,V/DexLibLoader( 4511): Creating class loader,
V/DexLibLoader( 4511): Finished creating class loader,
V/DexLibLoader( 4511): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4511): Dex already copied
D/OdexVerifier( 4511): Odex verification is skipped.
,V/DexLibLoader( 4511): Creating class loader,
V/DexLibLoader( 4511): Finished creating class loader
V/DexLibLoader( 4511): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4511): Dex already copied
D/OdexVerifier( 4511): Odex verification is skipped.
,V/DexLibLoader( 4511): Creating class loader,
V/DexLibLoader( 4511): Finished creating class loader
,V/DexLibLoader( 4511): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4511): DexLibLoader.ensureDexLoaded took 18 ms
,W/dalvikvm( 4511): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/SensorManager(  903): mEventCount = 1200
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 1
I/wpa_supplicant( 1162): wpa_s->is_screen_on 1
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 1
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8a7a4e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb8a7a4e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb8a79718 (mode change)
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a79718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb8a79718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
,D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1162): reply (489) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-47
I/wpa_supplicant( 1162): tsf=0000000108471178
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-56
I/wpa_supplicant( 1162): tsf=0000000108471194
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2,
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2427
I/wpa_supplicant( 1162): level=-76
I/wpa_supplicant( 1162): tsf=0000000108471200
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-57
I/wpa_supplicant( 1162): tsf=0000000108471190
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (4) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108471178, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 108471194, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 108471200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 108471190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 4 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
W/dalvikvm( 4511): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4511): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Connect event
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1162): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): Get randomness: len=32 entropy=5
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/,WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8a799f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed1b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    broadcast key
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1162): set send_ind_to_ndc = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1162): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WISPrService( 4188): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4188): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/FbInjectorInitializer( 4511): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(42e9a860): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d1ed8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d1ed8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4511): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4511): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4511): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3224
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3224:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  903): acquireWL(43560248): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2219 10028 null
I/ActivityManager(  903): Recipient 3224
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43ca1dc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2219 10028 null
,D/PMS     (  903): releaseWL(43560248): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
D/PMS     (  903): releaseWL(43ca1dc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4540 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): Util - no network available!
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1402): service - mHandler: cancel location update
D/AutoSetting( 1402): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4511): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4511): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4511): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4540): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4540): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4540): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4540): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  903): killProcessQuiet, pid=4263
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4554 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 4263:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4540/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4540/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4540/10078)
,I/ActivityManager(  903): Recipient 4263
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiService(  903): Client connection lost with reason: 4
,W/ContextImpl( 4511): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4511): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4511): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4511): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4511): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4511): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4511): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4511): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4511): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4511): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4511): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4511): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4511): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4511): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4511): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4511): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4511): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4511): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4511): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4571 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3889
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3889:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 9.996MB for 79892-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4571): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 10.031MB for 84664-byte allocation
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4571): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  903): Recipient 3889
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4571/10151)
,V/WebViewChromiumFactoryProvider( 4571): Binding Chromium to main looper Looper (main, tid 1) {41ae73c8}
,I/LibraryLoader( 4571): Expected native library version number "",actual native library version number ""
,I/chromium( 4571): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4571): Initializing chromium process, renderers=0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44136990 u0 ReceiverList{44102268 4511 com.facebook.katana/10026/u0 remote:440fb1e8}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44136990 u0 ReceiverList{44102268 4511 com.facebook.katana/10026/u0 remote:440fb1e8}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432b18d8 u0 ReceiverList{432a23f0 4511 com.facebook.katana/10026/u0 remote:4329bd18}}
,E/AudioManagerAndroid( 4571): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(4354f258): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(4362ee68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(4362ee68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4571): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4571): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4571): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4571): Local Branch: 
I/Adreno-EGL( 4571): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4571): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4571):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/PMS     (  903): acquireWL(435687a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
,D/PMS     (  903): releaseWL(435687a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NSApplication( 4571): Starting up...
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4571/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4571/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4166/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4166/10160)
,D/Process (  903): killProcessQuiet, pid=4010
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4010:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4010
D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCoreFlp( 1428): Unknown pending intent to remove.
D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
D/PMS     (  903): acquireWL(43c8fd70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
D/PMS     (  903): releaseWL(43c8fd70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4511): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4511): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4443): 
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f7840
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f7840, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e6668
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@420e0f08
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,W/PMS     (  903): mWirelessDisplayManager is null
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4443): 
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4443): 
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(42e9a860): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=100 [1][1][0]
I/wpa_supplicant( 1162): Change stage from stage0 to stage3
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48,
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1162): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19393 delay=15s
,D/WifiWatchdogStateMachine(  903): WAN detection
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4188): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4240e1b8
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(43001b30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=100 [1][1][0]
,I/wpa_supplicant( 1162): Change stage from stage3 to stage0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4540/10078)
D/PMS     (  903): acquireWL(42ffd378): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2219 10028 null
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  903): acquireWL(42f87990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2219 10028 null
D/PMS     (  903): releaseWL(42ffd378): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
I/CheckinService( 2219): Preparing to send checkin request
I/EventLogService( 2219): Accumulating logs since 1453125174709
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/GoogleHttpClient( 2219): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2219): Using GMS GoogleHttpClient
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2219/10028)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2219/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(43001b30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 374ms
,W/CheckinRequestBuilder( 2219): awaiting user notification for token
D/PMS     (  903): nativeSetInteractive:false
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41e5de08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425019d0)
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0
D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 7 4 12
,D/NfcService( 1253): applyRouting -2
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=4443
D/PMN     (  903): wakingUp
D/PMS     (  903): acquireWL(42d93158): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42d93158): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  903): No lock screen! windowToken=null
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
D/PMS     (  903): acquireWL(43c97718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMN     (  903): onScreenOn
D/PMS     (  903): releaseWL(43c97718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/MtpService( 2477): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2477): [MTP][onReceive]-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
,D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): acquireWL(424fcc90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  903): releaseWL(424fcc90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=98
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19394 delay=15s
,D/TetherSettings( 4188): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4188): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4188): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4188): Cust_ConnectToPC   : spcsc>false
D/        ( 4188): Cust_ConnectToPC   : IPT>true
,D/        ( 4188): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4188): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
E/SmartNS_Utility( 4188): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4188): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4188): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4654 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/PSReceiver( 4188): onReceive:android.intent.action.USER_PRESENT
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 120
,D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
W/ContextImpl( 4188): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/ClockThread( 1114): stop update clock
,I/SmartNS_PSService( 4188): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
W/Settings( 4188): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  903):    returned true
,I/SmartNS_PSService( 4188):  defaultType:0
D/WIFI_ICON( 1114): WifiActivity: 2
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/NetworkPolicy(  903): updateScreenOn: false
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/MultiDex( 4654): install
I/MultiDex( 4654): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4654): loading existing secondary dex files
I/MultiDex( 4654): load found 1 secondary dex files
I/MultiDex( 4654): install done
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4669 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ProviderInstaller( 4654): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOn: 1453125230752
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOn: 1453125230752
D/PMS     (  903): acquireWL(437e0270): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1428 10028 null
D/PMS     (  903): releaseWL(437e0270): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e6668
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420e6668, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@420e0f08
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
,D/PMS     (  903): acquireWL(42635e70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,W/ContextImpl( 4669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19394 mDataStallAlarmIntent=PendingIntent{425707a8: PendingIntentRecord{42597aa0 android broadcastIntent}}
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4669): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(425316b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/PMS     (  903): acquireWL(438a0ab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4669 1000 null
,D/SmartSyncUtils( 4669): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  903):    returned true
D/PMS     (  903): releaseWL(425316b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  903): releaseWL(438a0ab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  903): killProcessQuiet, pid=4298
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/SRS_Proc(  371): ParamSet string: screen_state=off
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Killing 4298:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  903): updateScreenOn: false
I/ActivityManager(  903): Recipient 4298
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=100 [1][1][0]
I/wpa_supplicant( 1162): Change stage from stage0 to stage3
,W/ContextImpl( 4669): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4669): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4669): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4669): isEpsOn(), nState = 0
,I/jxcore-log( 4443): Test app app.js loaded
I/jxcore-log( 4443): 
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420e0f08
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/ContactMessageStore( 1239): start background delete task...
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420e0f08, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
,I/Choreographer( 4443): Skipped 279 frames!  The application may be doing too much work on its main thread.
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420e0f08, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420e0f08
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  903): New client listening to asynchronous messages
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42039d80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42039d80 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/ResourceType( 4443): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aef5a8 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4443): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/AutoSetting( 1402): service - mHandler: cancel location update
D/AutoSetting( 1402): service -           changes count: 0
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): releaseWL(42635e70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  903): acquireWL(432a61e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1428 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOff
D/PMS     (  903): releaseWL(432a61e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/Adreno-EGL( 4654): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4654): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4654): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4654): Local Branch: 
I/Adreno-EGL( 4654): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4654): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4654):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4654/10028)
,I/Adreno-EGL( 4654): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4654): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4654): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4654): Local Branch: 
I/Adreno-EGL( 4654): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4654): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4654):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4654): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4654): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4654): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4654): Local Branch: 
I/Adreno-EGL( 4654): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4654): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4654):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4443): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4443): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4443): BLE advertisement is supported
I/jxcore-log( 4443): 
,D/PMS     (  903): releaseWL(42465168): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  903): bSetPropertyMultiRAB:false
I/NetworkMonitor( 3907): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/PMS     (  903): acquireWL(43d9c970): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
D/PMS     (  903): releaseWL(43d9c970): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3907/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1872/1000)
I/acms    ( 1872): Checking Certificates
I/acms    ( 1872): Checking Developer Certificates
I/acms    ( 1872): Checking Application Certificates
I/acms    ( 1872): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1872): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1872): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1872): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1872): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1872): Updating next query delay: 75600000
I/mlserverapp( 1872): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1872): cancelACMSProgrammedChecks
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4540/10078)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3929/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(42f4cbc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/Settings( 4654): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2477/10021)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(43a12978): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1329): Unsupported attribute readOnly
I/ActivityManager(  903): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4701 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  903): releaseWL(42f4cbc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(4356ad00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2219 10028 null
D/PMS     (  903): releaseWL(4356ad00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
,D/libc    ( 1366): [NET] getaddrinfo_proxy+
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
,D/PMS     (  903): acquireWL(43e0a6c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10028 null
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6e42 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4540): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4540): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1402): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4571/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4166/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4166/10160)
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1821/10178)
,I/dalvikvm-heap( 4166): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
,I/NewsWeather( 4701): LocationClient connecting
D/PMS     (  903): acquireWL(433a4420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  903): releaseWL(433a4420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4701): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4701): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4701): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4701): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4701): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,W/fb4a(:<default>):UserScope( 4511): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4511): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/GCM     ( 1366): Connected
,I/ProviderInstaller( 4701): Installed default security provider GmsCore_OpenSSL
D/PMS     (  903): acquireWL(42ec5390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  903): releaseWL(43e0a6c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(430edc50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42ec5390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(43cbce40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
,D/PMS     (  903): releaseWL(430edc50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4701): onConnected null
I/NewsWeather( 4701): Last usage 0, idle 1453125231s, sync interval 2592000s
,I/NewsWeather( 4701): setPeriodicSync in seconds 2592000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/PMS     (  903): acquireWL(43a87b70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
,W/GCoreFlp( 1428): No location to return for getLastLocation()
,I/NewsWeather( 4701): LocationClient onConnected: location null
D/PMS     (  903): acquireWL(4416b6e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1428 10028 null
D/PMS     (  903): releaseWL(43a87b70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1366): Message class mpf
I/NewsWeather( 4701): Skip sync for lookup editions
,I/NewsWeather( 4701): syncNewsAppData traffic type BACKGROUND_POLL
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  903): releaseWL(43cbce40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(43a3e7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  903): releaseWL(43a3e7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4701): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/PMS     (  903): releaseWL(4416b6e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,I/CheckinTask( 2219): Sending checkin request (8965 bytes)
D/libc    ( 2219): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2219): [NET] getaddrinfo-,err=8
D/libc    ( 2219): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2219): [NET] getaddrinfo-, 1
,D/libc    ( 2219): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =69fd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4701): Unrecoverable authentication exception
E/NewsWeather( 4701): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4701): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41b707f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 208
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2219): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4701): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4701): [NET] getaddrinfo-,err=8
I/RemoteViews.Performance( 1114): com.google.android.gms 1 11 3 12
D/libc    ( 4701): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4701): [NET] getaddrinfo-, 1
D/libc    ( 4701): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7c6e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4511): Called registerBroadcastReceiver twice.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4701): [NET] getaddrinfo_proxy-, success
D/libc    ( 2219): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2219): [NET] getaddrinfo-,err=8
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/libc    ( 4511): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4511): [NET] getaddrinfo-,err=8
D/libc    ( 4511): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4511): [NET] getaddrinfo-, 1
,D/libc    ( 4511): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b51e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    ( 4701): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4701): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 40
D/libc    (  364): [NET]res_nsend:resplen=74
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4511): [NET] getaddrinfo_proxy-, success
,I/global  ( 4511): call createSocket() return a new socket.
D/libc    ( 4511): [NET] getaddrinfo+,hn 12(0x3137392e36302e),sn(),family 0,flags 4
,D/libc    ( 4511): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=20 [30][6][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43d408c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,E/NewsWeather( 4701): Failed to syncNewsAppData
,E/NewsWeather( 4701): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  903): releaseWL(43d408c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43ce5b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67765, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  903): killProcessQuiet, pid=4329
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  903): releaseWL(43a12978): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
I/ActivityManager(  903): Killing 4329:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  903): releaseWL(43ce5b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4258dcf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(4258dcf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  903): Recipient 4329
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/libc    ( 4511): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4511): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(422eac08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  903): releaseWL(422eac08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): releaseWL(4354f258): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 10.974MB for 32784-byte allocation
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2219/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2219/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [4][0][0]
,I/dalvikvm-heap( 4511): Grow heap (frag case) to 11.000MB for 32784-byte allocation
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2219): awaiting user notification for token
D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41d87f80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 1 7 1 12
,I/CheckinTask( 2219): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2219): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(42f87990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2219): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c8fe60 that was originally bound here
E/ActivityThread( 2219): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c8fe60 that was originally bound here
E/ActivityThread( 2219): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2219): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2219): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2219): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2219): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2219): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2219): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2219): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2219): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2219): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2219): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2219): 	at bks.a(SourceFile:298)
E/ActivityThread( 2219): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2219): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2219): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1366): GCM config loaded
,D/PMS     (  903): acquireWL(4228b0c8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4511 10026 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4511/10026)
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c6f2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/104.81.130.175
,I/global  ( 4511): I/O error closing connection
I/global  ( 4511): java.net.SocketException: Socket is closed
I/global  ( 4511): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4511): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4511): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4511): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4511): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4511): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4511): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4511): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4511): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4511): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4511): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4511): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4511): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4511): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4511): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4511): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4511): Removing a connection that never existed!
D/PMS     (  903): releaseWL(4228b0c8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4571): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4345
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4345:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4345
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4701): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  903): killProcessQuiet, pid=4369
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4369:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4369
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42476218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b05e40: PendingIntentRecord{4234ace8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119965, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42476218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(425d3b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41cde058: PendingIntentRecord{42480a80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=128402, Int=0
,D/PMS     (  903): acquireWL(42ea5728): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(425d3b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426153c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42ea5728): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(426153c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(439efde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(439efde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=98
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1402): service - has update message, not stop
,D/AutoSetting( 1402): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1519): service - mHandler: update timezone
D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ec8220 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 8 2 11
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{442d93a8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(44111ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{42591d78: PendingIntentRecord{424c4a08 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140905, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1366/10028)
,V/AlarmManager(  903): sending alarm PendingIntent{422fcc58: PendingIntentRecord{420dfa20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140963, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{41cde058: PendingIntentRecord{42480a80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=158426, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(43651240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): acquireWL(43c3cc08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  903): acquireWL(43e19870): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/PMS     (  903): releaseWL(43c3cc08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  903): releaseWL(44111ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a26b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000),
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  903): acquireWL(4332a540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=17 [35][6][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43d315e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
,D/PMS     (  903): releaseWL(43e19870): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(4332a540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43db0948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/NewsWeather( 4701): Last usage 0, idle 1453125278s, sync interval 2592000s
,I/NewsWeather( 4701): setPeriodicSync in seconds 2592000
D/PMS     (  903): releaseWL(43db0948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
I/NewsWeather( 4701): Skip sync for lookup editions
,I/NewsWeather( 4701): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4701): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4701): Unrecoverable authentication exception
E/NewsWeather( 4701): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4701): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41b2abd0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 13 3 12
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): acquireWL(44143c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  903): releaseWL(44143c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4701): Failed to syncNewsAppData
,E/NewsWeather( 4701): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(435e7608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 112283, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  903): releaseWL(43d315e8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
,D/PMS     (  903): releaseWL(435e7608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(439c23a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(439c23a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  903): releaseWL(43651240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43941f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43941f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - onDestroy() END
,D/AutoSetting( 1402): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3929
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3929:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3929
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4387
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4387:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4387
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43946e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b05e40: PendingIntentRecord{4234ace8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179965, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43946e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(43d33840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41cde058: PendingIntentRecord{42480a80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=188514, Int=0
,D/PMS     (  903): acquireWL(43d62cc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/PMS     (  903): releaseWL(43d33840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4355c608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43d62cc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(4355c608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(43ad4750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ad4750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(44046750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41cde058: PendingIntentRecord{42480a80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=223287, Int=0
,D/PMS     (  903): acquireWL(42e8c790): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): releaseWL(44046750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43642ac8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=6 [50][3][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42ea85f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 903 1000 WorkSource{10106}
,D/PMS     (  903): releaseWL(42e8c790): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(43642ac8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(432a5f18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/NewsWeather( 4701): Last usage 0, idle 1453125343s, sync interval 2592000s
,I/NewsWeather( 4701): setPeriodicSync in seconds 2592000
D/PMS     (  903): releaseWL(432a5f18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4701): Skip sync for lookup editions
,I/NewsWeather( 4701): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4701): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/NewsWeather( 4701): Unrecoverable authentication exception
E/NewsWeather( 4701): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4701): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4701): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c1be70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 3 17 3 12
,D/PMS     (  903): acquireWL(43e8ccd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  903): releaseWL(43e8ccd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4701): Failed to syncNewsAppData
,E/NewsWeather( 4701): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4391d270): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/SyncManager(  903): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 158955, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  903): releaseWL(42ea85f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): releaseWL(4391d270): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1428/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(43615c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43615c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  903): acquireWL(43e676d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{4389c960: PendingIntentRecord{43439b88 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229408, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4758 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{4240b328: PendingIntentRecord{423f47f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453125339867, Int=10800000
,D/PMS     (  903): releaseWL(43e676d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4758/10047),
,D/Process (  903): killProcessQuiet, pid=4316
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4316:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4316
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(440f1a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{426256e0: PendingIntentRecord{43956e00 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230497, Int=120000
,V/AlarmManager(  903): sending alarm PendingIntent{43cb9650: PendingIntentRecord{43439b88 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230749, Int=0
,D/PMS     (  903): releaseWL(440f1a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2219/10028)
,D/PMS     (  903): acquireWL(4241d308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4241d308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=99
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(435fd158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b05e40: PendingIntentRecord{4234ace8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239965, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(435fd158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43688a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43688a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43fdf8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41cde058: PendingIntentRecord{42480a80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=253345, Int=0
,D/PMS     (  903): acquireWL(425b3050): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/PMS     (  903): releaseWL(43fdf8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(4390ac50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(425b3050): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(4390ac50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(430fe8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b05e40: PendingIntentRecord{4234ace8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=299965, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(430fe8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43a2f518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a2f518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4443): --= Surplus to requirements =--
I/jxcore-log( 4443): 
I/jxcore-log( 4443): ****TEST TOOK:  ms ****
I/jxcore-log( 4443): 
,I/jxcore-log( 4443): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4443): 
,E/cutils-trace( 4780): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4780): ====startRecUseTime====
D/htc.customization.log.level( 4780):  is 
,W/CustomizationLogLevel( 4780): Level value is invalid, use default level 2
,D/CustomizationManager( 4780):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 4780): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4780): Parsing tag item name = HTC__031,
V/CustomizationCIDLoader( 4780): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4780): Parsing tag category name = system
,I/CustomizationCIDLoader( 4780): Parsing tag category name = application
I/CustomizationCIDLoader( 4780): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4780): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4780): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4780): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4780): Parsing tag category name = Settings
D/CustomizationManager( 4780):  Read CID file spent 0.155 (s)
,D/CustomizationManager( 4780):  All configurations done spent 0.155 (s),
,W/HtcNativeFlag( 4780): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4780): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4780): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4780): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4780, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=4443
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  903): Killing 4443:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903):   Force finishing activity ActivityRecord{41d24128 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  903): Copying FileAsset 0x6f4115e8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  903): channel '42393b50 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  903): channel '42393b50 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '42393b50 com.test.thalitest.MainActivity (s)'
I/WindowManager(  903): WINDOW DIED Window{42393b50 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
,W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4443 uid 10189
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/dalvikvm-heap( 4166): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,W/GeofencerStateMachine( 1428): Ignoring removeGeofence because network location is disabled.
D/PMS     (  903): acquireWL(43e43c38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1428 10028 null
,D/PMS     (  903): releaseWL(43e43c38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1872): Unregistering com.test.thalitest
E/acms    ( 1872): Could not unregister removed application com.test.thalitest
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Launcher( 1268): Deferring update until onResume
D/Launcher( 1268): waitUntilResume // bindAppsRemoved
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
,D/PackageBroadcastService( 2219): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
,I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4797 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4797): install
,I/MultiDex( 4797): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4797): loading existing secondary dex files
,I/MultiDex( 4797): load found 1 secondary dex files
,I/MultiDex( 4797): install done
,I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4817 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 2219): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2219, uid=10028, userID:0
,I/Icing   ( 2219): doRemovePackageData com.test.thalitest
,D/PMS     (  903): acquireWL(421b7670): PARTIAL_WAKE_LOCK  Icing 0x1 2219 10028 null
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2219): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2219): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2219): Writing status failed
,E/Icing   ( 2219): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 2219): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 2219): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 2219): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 2219): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 2219): 	at ghk.a(SourceFile:192)
E/Icing   ( 2219): 	at gga.n(SourceFile:1223)
E/Icing   ( 2219): 	at gdz.q(SourceFile:2247)
E/Icing   ( 2219): 	at ger.run(SourceFile:301)
E/Icing   ( 2219): 	at ght.a(SourceFile:259)
E/Icing   ( 2219): 	at ghz.d(SourceFile:73)
E/Icing   ( 2219): 	at ghu.run(SourceFile:250)
E/Icing   ( 2219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 2219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 2219): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 2219): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 2219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 2219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 2219): 	at ghy.run(SourceFile:50)
E/Icing   ( 2219): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 2219): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 2219): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 2219): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 2219): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 2219): 	... 17 more
D/PMS     (  903): releaseWL(421b7670): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4797): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/MultiDex( 4817): install
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4817): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4817): loading existing secondary dex files
,I/MultiDex( 4817): load found 1 secondary dex files
,I/MultiDex( 4817): install done
,E/SQLiteDatabase( 2219): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2219): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2219): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2219): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2219): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2219): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2219): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ClearPendingStateOp( 2219): Runtime exception while performing operation
E/ClearPendingStateOp( 2219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2219): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2219): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2219): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2219): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2219): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2219): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,F/ClearPendingStateOp( 2219): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2219): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2219): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2219): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2219): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2219): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2219): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  903): Resuming delayed broadcast
,E/SharedPreferencesImpl( 1207): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
,I/ProviderInstaller( 4817): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1402): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,E/SQLiteLog( 1402): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,E/SQLiteDBG( 1402): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca0a010
,W/[PluginManager]RegisterService( 1402): provider may killed!
W/[PluginManager]RegisterService( 1402): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1402): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1402): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1402): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1402): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1402): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1402): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  903): Can't write: system_app_wtf
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
,I/[PluginManager]RegisterService( 1402): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=4402
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1268): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  903): Killing 4402:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4402
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2906): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4839 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteLog( 2906): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64400fe8
,W/dalvikvm( 2906): threadid=16: thread exiting with uncaught exception (group=0x416b0e30)
E/AndroidRuntime( 2906): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2906): Process: com.google.android.googlequicksearchbox:search, PID: 2906
E/AndroidRuntime( 2906): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2906): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2906): 	at cid.d(PG:186)
E/AndroidRuntime( 2906): 	at clo.g(PG:594)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2906): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2906): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2906): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2906): 	at clr.tL(PG:827)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2906): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2906): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2906): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
,D/Process ( 2906): killProcess, pid=2906
,D/Process ( 2906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
,E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4797): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4797): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4797): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4797): threadid=13: thread exiting with uncaught exception (group=0x416b0e30)
,E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4797): killProcess, pid=4797
,D/Process ( 4797): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4797): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4797): Process: com.google.android.gms.drive, PID: 4797
E/AndroidRuntime( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4797): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4797): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4797): 	at ctn.run(SourceFile:985)
I/ActivityManager(  903): Recipient 2906
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2906) has died.
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2906): Died!
D/WifiService(  903): Client connection lost with reason: 4
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
E/DropBoxManagerService(  903): Can't write: system_app_crash
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
,I/ActivityManager(  903): Recipient 4797
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4797) has died.
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10870ms
,E/SQLiteDatabase( 4839): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.,
E/SQLiteDatabase( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
,E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4839): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4839): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4839): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4839): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4839): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4839): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4839): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4839): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4839): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4839): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4839): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4839): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4839): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4839): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4839): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4839): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4839): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4839): 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4839): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4839): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4839): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4839): ,	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4839): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4839): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4839): ,	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4839): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4839): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4839): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4839): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4839): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4839): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
,E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4839): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4839): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4839): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4839): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4839): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4839): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4839): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4839): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4839): threadid=11: thread exiting with uncaught exception (group=0x416b0e30)
,E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4839): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4839): Process: com.google.android.apps.docs, PID: 4839
E/AndroidRuntime( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4839): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4839): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4839): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4839): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4839): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  903): Can't write: system_app_crash
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
,D/Process ( 4839): killProcess, pid=4839
,D/Process ( 4839): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4859 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/Prism.ItemManager( 1268): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1268): loadItems() com.htc.launcher.pageview.WidgetManager@41b73f50 +
,I/Prism.WidgetManager( 1268): onLoadItems() +
,I/ActivityManager(  903): Recipient 4839
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=4487
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4487:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4839) has died.
,I/ActivityManager(  903): Recipient 4487
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4872 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4859): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4859): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4859): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4859): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4859): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4859): threadid=10: thread exiting with uncaught exception (group=0x416b0e30)
E/AndroidRuntime( 4859): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4859): Process: com.android.keychain, PID: 4859
E/AndroidRuntime( 4859): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4859): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4859): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4859): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4859): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4859): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4859): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4859): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4859): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  903): App crashed! Process: com.android.keychain
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox

```
