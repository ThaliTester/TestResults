#### Test 56204092c98eeae_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  905): acquireWL(41f435e0): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  905): releaseWL(41f435e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(42071c20): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  905): releaseWL(42071c20): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  905): acquireWL(43125de8): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  905): releaseWL(43125de8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(4267d530): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  905): releaseWL(4267d530): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
E/cutils-trace( 4450): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4450): ====startRecUseTime====
D/htc.customization.log.level( 4450):  is 
W/CustomizationLogLevel( 4450): Level value is invalid, use default level 2
D/CustomizationManager( 4450):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4450): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4450): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4450): Parsing tag category name = system
I/CustomizationCIDLoader( 4450): Parsing tag category name = application
I/CustomizationCIDLoader( 4450): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4450): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4450): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4450): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4450): Parsing tag category name = Settings
D/CustomizationManager( 4450):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4450):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4450): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4450): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4450): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4450): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4450
D/PMS     (  905): acquireHCC(423a31f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42082048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62f93fe8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1111693216
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fa7b88
D/PMS     (  905): acquireWL(4252b068): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4461 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4461): Copying FileAsset 0x5c7a1428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4461): Binding Chromium to main looper Looper (main, tid 1) {41b216f0}
I/LibraryLoader( 4461): Expected native library version number "",actual native library version number ""
I/chromium( 4461): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4461): Initializing chromium process, renderers=0
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4426aef8:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4461): 1102283128: getState(). Returning 12
D/PMS     (  905): acquireWL(41b31d30): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(442a0ed0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(442a0ed0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4461): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4461): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4461): Local Branch: 
I/Adreno-EGL( 4461): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4461): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4461):                  aa63bbd948f41d15fc72f585e
W/chromium( 4461): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4461): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4461): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4461): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4461): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4461): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4461): CordovaWebView is running on device made by: HTC
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4489 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(425e5970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{42383f90: PendingIntentRecord{422a9360 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452883492970, Int=60000
D/PMS     (  905): releaseWL(425e5970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/SMSBackup( 4489): SMSBackupAgentService started
D/SMSBackup( 4489): Checking restore status
D/SMSBackup( 4489): Restore complete
D/SMSBackup( 4489): cancelCheckAlarm
D/SMSBackup( 4489): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  905): killProcessQuiet, pid=4234
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  905): Killing 4234:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
W/AwContents( 4461): nativeOnDraw failed; clearing to background color.
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 6
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 24
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/InputMethodManagerService(  905): Disable input method client, pid=1271
,W/ResourceType( 4461): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4461): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b69828, mServedView=org.apache.cordova.engine.SystemWebView{41b2f490 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Enable input method client, pid=4461
,W/AwContents( 4461): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +285ms
,D/PMS     (  905): releaseWL(4252b068): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4234
,D/PMS     (  905): acquireWL(424cbaf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
,D/PMS     (  905): acquireWL(4236c758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
,D/PMS     (  905): releaseWL(424cbaf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(4236c758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/JsMessageQueue( 4461): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4461): JniHelper::setJavaVM(0x415f8048), pthread_self() = 1663994632
,D/JX-Cordova( 4461): jxcore cordova android initializing
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 11.944MB for 42938-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.021MB for 96598-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.101MB for 144892-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.216MB for 217334-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.393MB for 325996-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 12.666MB for 488990-byte allocation
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 13.653MB for 1100216-byte allocation
,I/SensorManager(  905): mEventCount = 1201
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 14.596MB for 1650320-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 15.857MB for 2475476-byte allocation
,I/dalvikvm-heap( 4461): Grow heap (frag case) to 18.045MB for 3713210-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(423a31f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42082048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=135 rxSum=126} preTxRxSum={txSum=129 rxSum=122}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19324 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19325 delay=15s
D/PMS     (  905): acquireWL(425f5870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42449d40: PendingIntentRecord{424b4ce0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105496, Int=0
D/PMS     (  905): releaseWL(425f5870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/jxcore-log( 4461): Initializing JXcore engine
,W/jxcore-log( 4461): JXcore engine is ready
,W/jxcore-log( 4461): Starting JXcore engine
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4461): Platform android
W/jxcore-log( 4461): 
,W/jxcore-log( 4461): Process ARCH arm
W/jxcore-log( 4461): 
,D/PMS     (  905): releaseWL(41b31d30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4461): JXcore Cordova bridge is ready!
I/jxcore-log( 4461): 
,W/jxcore-log( 4461): JXcore engine is started
I/chromium( 4461): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 6
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 30
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:187, mTXpacketCount:183, avgLinkspeed:6,mAvgTxRate54
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4461): Toggling radios to true
I/jxcore-log( 4461): 
,D/BluetoothAdapter( 4461): enable(): BT is already enabled..!
,D/WifiManager( 4461): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1298
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 0(ms)
,D/WifiManager( 4461): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
,D/WifiManager( 4461): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): TDLS: Tear down peers
,I/wpa_supplicant( 1157): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4461): Radios toggled
I/jxcore-log( 4461): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4461, uid=10189
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4461): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4461): 
I/jxcore-log( 4461): Perf Test app loaded loaded
I/jxcore-log( 4461): 
I/Choreographer( 4461): Skipped 90 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4461): check test folder
I/jxcore-log( 4461): 
,I/jxcore-log( 4461): found test : ./testFindPeers.js
I/jxcore-log( 4461): 
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1157): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1157): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1157): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb81c9bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1157): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
I/jxcore-log( 4461): found test : ./testSendData.js
I/jxcore-log( 4461): 
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42127f98): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): Fast associate: Old scan results
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): State: DISCONNECTED -> SCANNING
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19325 mDataStallAlarmIntent=PendingIntent{4254d380: PendingIntentRecord{424b4ce0 android broadcastIntent}}
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/libc    (  364): [NET] entry_id:6   entry:0xb84b9808  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb84b9890  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb84bdf10  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb84b9738  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb84b9980  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb84b9428  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb84b4d28  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb84b48b0  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb84be0b0  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb84b4ed0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
D/PMS     (  905): acquireWL(423e6030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1387 10028 null
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/PMS     (  905): acquireWL(42e85f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  364): RTNETLINK answers: No such process
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1387/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(42c9c4a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42e85f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1157): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  905): releaseWL(423e6030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  905): releaseWL(42c9c4a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4461): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  905): NoActiveNetworkState
I/Tethering(  905): ipv4Default null
,I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(425dd888): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(425dd888): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
,I/NetworkMonitor( 3896): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4347/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3896/10154)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4347/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2475/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4527 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4527): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4527): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4527): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4527): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4527): Preparing secondary program dexes.
V/DexLibLoader( 4527): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4527): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4527): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4527): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4527): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4527): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4527): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped.
,V/DexLibLoader( 4527): Creating class loader,
V/DexLibLoader( 4527): Finished creating class loader
,V/DexLibLoader( 4527): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4527): DexLibLoader.ensureDexLoaded took 18 ms
,W/dalvikvm( 4527): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4527): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4527): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1157): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-86
I/wpa_supplicant( 1157): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-91
I/wpa_supplicant( 1157): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1157): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1157): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1157): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1157): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1157): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1157): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1157): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1157): Start print parameters
I/,wpa_supplicant( 1157): wpa_s->wpa_state is 3
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 1
I/wpa_supplicant( 1157): wpa_s->is_screen_on 1
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): selected network = 1
D/wpa_supplicant( 1157): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81cb4e8  current_ssid=0x0
D/wpa_supplicant( 1157): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1157): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1157): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1157): check if in concurrent case
I/wpa_supplicant( 1157): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1157): RSN: PMKSA cache search - network_ctx=0xb81cb4e8 try_opportunistic=0
D/wpa_supplicant( 1157): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1157): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1157): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1157): nl80211: Unsubscribe mgmt frames handle 0xb81ca718 (mode change)
D/wpa_supplicant( 1157): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81ca718
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb81ca718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1157):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157):   * freq=2412
D/wpa_supplicant( 1157):   * Auth Type 0
D/wpa_supplicant( 1157):   * WPA Versions 0x2
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1157): nl80211: Connect request send successfully
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1157): reply (924) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-48
I/wpa_supplicant( 1157): tsf=0000000110451161
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-60
I/wpa_supplicant( 1157): tsf=0000000110451178
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2452
I/wpa_supplicant( 1157): level=-77
I/wpa_supplicant( 1157): tsf=0000000110451182
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-60
I/wpa_supplicant( 1157): tsf=0000000110451174
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=4
I/wpa_supplicant( 1157): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-86,
I/wpa_supplicant( 1157): tsf=0000000110451186
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=5
I/wpa_supplicant( 1157): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000110451190
I/wpa_supplicant( 1157): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=UPC Wi-Free
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=6
I/wpa_supplicant( 1157): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1157): freq=2437
I/wpa_supplicant( 1157): level=-91
I/wpa_supplicant( 1157): tsf=0000000110451194
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=UPC4688432
I/wpa_supplicant( 1157): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 110451161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 110451178, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 110451182, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -60, frequency: 2412, timestamp: 110451174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -86, frequency: 2437, timestamp: 110451186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2437, timestamp: 110451190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 110451194, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
,D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/fb4a(:<default>):StaticBindingVerifier( 4527): Verify
,I/PMS     (  905): Going to sleep due to screen timeout...
,D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4219e670
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Connect event
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1157): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Add randomness: count=13 entropy=7
I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on association
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1157): EAPOL: enable timer tick
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1157): Get randomness: len=32 entropy=8
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  905): Couldn't get kernel wake lock stats
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4219e670, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42394f98
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41b34f68
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true,
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb81ca9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f77b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1157): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1157): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1157): set send_ind_to_ndc = 0
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  905): setLight #0: color=#0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1157): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1157): EAPOL authentication completed successfully
I/wpa_supplicant( 1157): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,W/PMS     (  905): mWirelessDisplayManager is null
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(427b38d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 1
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c8638 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c8638 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  905): acquireWL(433a2970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110691, Int=0
,D/PMS     (  905): releaseWL(433a2970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1116): now=1452883500058 next=59942
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 369ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
W/ResourceType( 4461): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4461): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b2f490 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4461
D/PMS     (  905): acquireWL(43e513e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  905): releaseWL(43e513e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44190d58)
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/WifiService(  905): New client listening to asynchronous messages
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(442845a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
I/BatteryService(  905): n_update end
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:On
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1157): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): releaseWL(442845a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  905): onScreenOn
D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiNative-wlan0(  905):    returned true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1256): applyRouting - 0
,D/MtpService( 2475): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2475): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting -2
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): acquireWL(43e787b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  905): releaseWL(43e787b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/ClockThread( 1116): stop update clock
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/fb4a(:<default>):BaseAnalyticsConfig( 4527): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4527): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1827): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1827): onScreenOn: 1452883500388
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1827): onScreenOn: 1452883500388
D/PMS     (  905): acquireWL(441e19e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1496 10028 null
D/PMS     (  905): releaseWL(441e19e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42394f98
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42394f98, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41b34f68
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(42e36fb0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19326 mDataStallAlarmIntent=null
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:Off
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1157): get_ip_address source addr = 02000000
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  905): acquireWL(43e0a3a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(42e36fb0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  905): releaseWL(43e0a3a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3393
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3393:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3393
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42840808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,D/PMS     (  905): acquireWL(43246630): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  905): releaseWL(42840808): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/AutoSetting( 1425): service - mHandler: cancel location update
,D/AutoSetting( 1425): service -           changes count: 0
,D/GCM     ( 1387): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): acquireWL(426c55a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1496 10028 null
D/PMS     (  905): releaseWL(43246630): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/PMS     (  905): releaseWL(426c55a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1827): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1827): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1827): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1827): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1827): onScreenOff
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/AutoSetting( 1425): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4568 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1425/10053)
,D/AutoSetting( 1425): Util - no network available!
,D/AutoSetting( 1425): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1425): service - mHandler: cancel location update
,D/AutoSetting( 1425): service -           changes count: 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1425/10053)
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4527): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4568): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4568): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4568): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4568): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  905): killProcessQuiet, pid=3880
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4582 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3880:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4568/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4568/10078)
I/ActivityManager(  905): Recipient 3880
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4568/10078)
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4596 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  905): Killing 4287:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4287
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4527): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ActivityManager(  905): Recipient 4287
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.956MB for 84664-byte allocation
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4527): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4527): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4527): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4527): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4596): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.970MB for 28144-byte allocation
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4527): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4527): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4527): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4527): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4527): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4527): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.089MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,V/WebViewChromiumFactoryProvider( 4596): Binding Chromium to main looper Looper (main, tid 1) {41b27350}
,I/LibraryLoader( 4596): Expected native library version number "",actual native library version number ""
I/chromium( 4596): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4596): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43db4d98): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4596): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(44195778): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(43db4d98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4596): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4596): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4596): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4596): Local Branch: 
I/Adreno-EGL( 4596): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4596): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4596):                  aa63bbd948f41d15fc72f585e
,D/wpa_supplicant( 1157): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1157): EAPOL: disable timer tick
,I/NSApplication( 4596): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4195/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4195/10160)
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.274MB for 75760-byte allocation
,D/Process (  905): killProcessQuiet, pid=4317
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4317:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,I/ActivityManager(  905): Recipient 4317
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43718210 u0 ReceiverList{437180f0 4527 com.facebook.katana/10026/u0 remote:4357bd18}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43718210 u0 ReceiverList{437180f0 4527 com.facebook.katana/10026/u0 remote:4357bd18}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e27c00 u0 ReceiverList{43e27ba0 4527 com.facebook.katana/10026/u0 remote:43a35af0}}
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4635 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/PMS     (  905): acquireWL(443038c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
,D/PMS     (  905): releaseWL(443038c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(442feab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
,D/GCoreFlp( 1496): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(442fe930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
D/PMS     (  905): releaseWL(442fe930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(442feab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4347
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1425): receiver - intent: android.intent.action.USER_PRESENT
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Killing 4347:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1425): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3827): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3827): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3827): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3827): Cust_ConnectToPC   : spcsc>false
D/        ( 3827): Cust_ConnectToPC   : IPT>true
D/        ( 3827): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3827): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3827): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3827): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3827): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3827): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3827): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3827): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3827):  defaultType:0
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ActivityManager(  905): Recipient 4347
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b34f68
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b34f68, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b34f68, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/GCM     ( 1387): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b34f68
,W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42456f48 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42456f48 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(427b38d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState,
D/WifiStateMachine(  905): VerifyingLinkState enter
,D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4244f290
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
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
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(41ff1de0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4568/10078)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=100 [1][1][0]
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,D/PMS     (  905): acquireWL(41ffbc40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(439ccfa8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
D/PMS     (  905): releaseWL(41ffbc40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,I/CheckinService( 2225): Preparing to send checkin request
,I/EventLogService( 2225): Accumulating logs since 1452883443087
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2225): Using GMS GoogleHttpClient
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(41ff1de0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b6aca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 0 9 4 12
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4693 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4693): install
,I/MultiDex( 4693): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false),
,I/MultiDex( 4693): loading existing secondary dex files
,I/MultiDex( 4693): load found 1 secondary dex files
,I/MultiDex( 4693): install done
,I/ProviderInstaller( 4693): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1387): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4461): threadid=1: thread exiting with uncaught exception (group=0x416f0e30)
,E/AndroidRuntime( 4461): FATAL EXCEPTION: main
E/AndroidRuntime( 4461): Process: com.test.thalitest, PID: 4461
E/AndroidRuntime( 4461): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4461): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4461): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4461): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4461): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4461): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4461): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4461): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4461): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4461): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4461): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4461): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.test.thalitest
W/ActivityManager(  905):   Force finishing activity com.test.thalitest/.MainActivity
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=4370
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 4370:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4370
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4461): killProcess, pid=4461
,D/Process ( 4461): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/Settings( 4693): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4461 uid 10189
,I/ActivityManager(  905): Recipient 4461
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{4237cf90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Process com.test.thalitest (pid 4461) has died.
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
D/PMS     (  905): releaseWL(42127f98): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
D/PMS     (  905): acquireWL(426a2b90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3896/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4568/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/NetworkMonitor( 3896): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1,
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3920/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
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
I/mlserverapp( 1895): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(442c90a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2475/10021)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(436f1710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4716 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  905): releaseWL(442c90a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(426a2b90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4693/10028)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(432203d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
D/PMS     (  905): releaseWL(432203d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1387): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/libc    ( 1387): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1387): [NET] getaddrinfo-,err=8
D/libc    ( 1387): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1387): [NET] getaddrinfo-, 1
,D/libc    ( 1387): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/PMS     (  905): acquireWL(4421c310): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1387 10028 null
D/libc    (  364): [NET] +++++ res_nsend xid =d334 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1425): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4568): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4568): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1425/10053)
,D/AutoSetting( 1425): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/AutoSetting( 1425): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1425): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1425): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1425/10053)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4195/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4195/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1852/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 167
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1387): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4195): Grow heap (frag case) to 13.517MB for 1821008-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 1387): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1387): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/NewsWeather( 4716): LocationClient connecting
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): acquireWL(426acfe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(426acfe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1509): service - onDestroy() END
D/AutoSetting( 1509): service - handleMessage() quit looper
I/NewsWeather( 4716): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4716): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4716): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4716): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4716): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/GCM     ( 1387): Connected
D/PMS     (  905): acquireWL(442a10e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1387 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): releaseWL(4421c310): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1387/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): releaseWL(442a10e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42568dd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1387 10028 null
,I/ProviderInstaller( 4716): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(427b3a70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(427b3a70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4716): Last usage 0, idle 1452883503s, sync interval 2592000s
,I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
,D/GCM     ( 1387): Message class mpf
,I/NewsWeather( 4716): onConnected null
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1387/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1387/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): acquireWL(43720e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
W/GCoreFlp( 1496): No location to return for getLastLocation()
,I/NewsWeather( 4716): LocationClient onConnected: location null
D/PMS     (  905): releaseWL(42568dd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): releaseWL(43720e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): acquireWL(4430b288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
D/PMS     (  905): acquireWL(43881fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1496 10028 null
D/PMS     (  905): releaseWL(4430b288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4527): Called registerBroadcastReceiver twice.
I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
D/PMS     (  905): releaseWL(43881fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/CheckinTask( 2225): Sending checkin request (8972 bytes)
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2225): [NET] getaddrinfo-, 1
D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2d9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 241
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41cd0870 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4716): [NET] getaddrinfo-,err=8
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4716): [NET] getaddrinfo-, 1
,D/libc    ( 4716): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
I/RemoteViews.Performance( 1116): com.google.android.gms 4 7 3 12
D/libc    (  364): [NET] +++++ res_nsend xid =d32e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4716): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43da4700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(43da4700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=14 [28][4][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43cc4fc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68249, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(436f1710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  905): killProcessQuiet, pid=4386
I/ActivityManager(  905): Killing 4386:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(44195778): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/PMS     (  905): releaseWL(43cc4fc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4353d880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
I/ActivityManager(  905): Recipient 4386
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(4353d880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(44274f98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(44274f98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41ecd7b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 10 4 12
,I/CheckinTask( 2225): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2225): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/GCM     ( 1387): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(439ccfa8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf4e68 that was originally bound here
E/ActivityThread( 2225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf4e68 that was originally bound here
E/ActivityThread( 2225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2225): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2225): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2225): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2225): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2225): 	at bks.a(SourceFile:298)
E/ActivityThread( 2225): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2225): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2225): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1387): GCM config loaded
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =165f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.44.209.153,
,I/GAV2    ( 4596): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV4    ( 4716): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4405
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4405:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4405
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3920
,I/ActivityManager(  905): Killing 3920:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3920
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1425): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1425): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1425): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.,
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  905): acquireWL(4346d7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=129697, Int=0
,D/PMS     (  905): acquireWL(43c61fe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null,
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4346d7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44207b00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43c61fe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(44207b00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(43aba660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(43aba660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4387d670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4387d670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1425): service - mHandler: update timezone
,D/AutoSetting( 1425): service - handleMessage() stop self
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1509): service - onCreate()
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1509): service - mHandler: update timezone
D/AutoSetting( 1425): service - handleMessage() quit looper
D/AutoSetting( 1425): service - onDestroy() END
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1509): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1509): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41eff8d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4430a3d0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43e40638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
D/PMS     (  905): acquireWL(43ce6118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/AlarmManager(  905): sending alarm PendingIntent{4205e970: PendingIntentRecord{420f40b8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140839, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{432770b0: PendingIntentRecord{424bc0e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141196, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=159729, Int=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/PMS     (  905): acquireWL(43dbc978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): acquireWL(42e656d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
D/PMS     (  905): releaseWL(43e40638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =975d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): acquireWL(44239b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42e656d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(4423e0d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(43dbc978): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(44239b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4425b5c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4425b5c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4716): Last usage 0, idle 1452883549s, sync interval 2592000s
I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,I/global  (  905): call createSocket() return a new socket.,
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b8ee38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 4 9 3 12
,D/PMS     (  905): acquireWL(4425e3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(4425e3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4423df10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 114538, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(4423e0d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(4423df10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/PMS     (  905): acquireWL(43db2c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43db2c28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): releaseWL(43ce6118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43710fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43710fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4334
,I/ActivityManager(  905): Killing 4334:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PMS     (  905): acquireWL(4370d6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{42424898: PendingIntentRecord{42784ae8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174093, Int=0
,D/PMS     (  905): releaseWL(4370d6f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/ActivityManager(  905): Recipient 4334
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(4370c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=189801, Int=0
,D/PMS     (  905): acquireWL(4370c390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4370c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4370a760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4370c390): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4370a760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4309d3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4309d3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4305fdc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=226153, Int=0
,D/PMS     (  905): acquireWL(42fe9780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(4305fdc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42e958d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=2 [35][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(4211b7f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42fe9780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(42e958d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42474928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42474928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4716): Last usage 0, idle 1452883615s, sync interval 2592000s
I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL,
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b2be40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 11 4 12
,D/PMS     (  905): acquireWL(423fc0c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/PMS     (  905): releaseWL(423fc0c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43707ec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 160337, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(4211b7f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
,D/PMS     (  905): releaseWL(43707ec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(423fe8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(423fe8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(424cbaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424cbaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4260dab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4260dab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(423978a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=256197, Int=0
,D/PMS     (  905): acquireWL(42e8cee0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(423978a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4254cf70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42e8cee0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4254cf70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(439b61c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(439b61c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42566070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(42566070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d17890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d17890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(424cea10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=350692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424cea10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43ceb190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=358247, Int=0
,D/PMS     (  905): acquireWL(42395bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43ceb190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42505b30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=6 [29][2][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(4277d558): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42395bf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  905): releaseWL(42505b30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4211b960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(4211b960): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4716): Last usage 0, idle 1452883747s, sync interval 2592000s
,I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41cc26e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 15 4 12
,D/PMS     (  905): acquireWL(4321c508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(4321c508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 226616, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42e8dbf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(4277d558): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  905): releaseWL(42e8dbf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(431ee130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(431ee130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1387): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1387): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1387): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1387): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1387): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1387): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1387): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1387): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41cb6558 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 11 3 12
,E/PlayEventLogger( 4157): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4157): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4157): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4157): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4157): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4157): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4157): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4157): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4157): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4157): [NET] getaddrinfo-,err=8
D/libc    ( 4157): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4157): [NET] getaddrinfo-, 1
,D/libc    ( 4157): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =672 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 127
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4157): [NET] getaddrinfo_proxy-, success
,I/global  ( 4157): call createSocket() return a new socket.
D/libc    ( 4157): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4157): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4157): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4157): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(437436d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437436d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(4258efc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=388306, Int=0
,D/PMS     (  905): acquireWL(42638c08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4258efc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4380b9a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42638c08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4380b9a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(425df030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425df030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43ccddc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43ccddc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(425caf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=470691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425caf70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43dd8be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(43dd8be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/TetherSettings( 3827): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3827): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3827): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3827): Cust_ConnectToPC   : spcsc>false
D/        ( 3827): Cust_ConnectToPC   : IPT>true
D/        ( 3827): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3827): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3827): Index of the first 1 = 3
W/Settings( 3827): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3827): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3827): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3827): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3827): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(434843c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(434843c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43e1c7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=530691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e1c7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42593658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42593658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  411): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4402ccc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4402ccc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43706250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=590692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43706250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44195870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(44195870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(439cd360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(439cd360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(44259cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=622033, Int=0
,D/PMS     (  905): acquireWL(4268a1b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(44259cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(442c7828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=13 [43][6][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4427a0e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(4268a1b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(442c7828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43a54940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43a54940): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4716): Last usage 0, idle 1452884011s, sync interval 2592000s
,I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41ea35d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4716): [NET] getaddrinfo-, 1
D/libc    ( 4716): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6c5a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4716): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 8 4 12,
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43726298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(43726298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44265540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 358770, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(4427a0e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(44265540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(442cf9e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(442cf9e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(4381f290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=650691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4381f290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c6efb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): releaseWL(42c6efb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4265e3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=652105, Int=0
,D/PMS     (  905): acquireWL(4334feb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4265e3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(438b69c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4334feb0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(438b69c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(42611188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42611188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(442605c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=710691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(442605c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43d7e0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d7e0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/Process (  905): killProcessQuiet, pid=4419
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4419:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4419
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43c61e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43c61e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(438d3f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=770692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438d3f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43ddfc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(43ddfc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(442e58d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(442e58d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426a3df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=830691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426a3df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(433b0510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(433b0510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435dc3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=890692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(435dc3c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(442ef5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(442ef5e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425727a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425727a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425d60d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950691, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425d60d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44262248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44262248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/PMS     (  905): runPSCheck
,D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(446583a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(446583a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44284260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44284260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/PMS     (  905): acquireWL(442823a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf2c0: PendingIntentRecord{42459a48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785723, Int=0
,D/ConnectivityService(  905): Done.
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4806 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  905): sending alarm PendingIntent{4256e598: PendingIntentRecord{4254cd88 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452883609824, Int=10800000
D/ConnectivityService(  905): Setting timer for 720seconds
,V/AlarmManager(  905): sending alarm PendingIntent{42af6298: PendingIntentRecord{4265ca30 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452884079327, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{426342e0: PendingIntentRecord{4263d968 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452884330010, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{42582d70: PendingIntentRecord{43d61870 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452884401295, Int=0
,D/PMS     (  905): acquireWL(44260c28): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2225 10028 null
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(4425e3b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2225 10028 null
,I/EventLogService( 2225): Aggregate from 1452883501945 (log), 1452882279278 (data)
D/PMS     (  905): releaseWL(44260c28): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PowerUsageService( 4635): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4635): MY_DEBUG = false
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/PMS     (  905): releaseWL(442823a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  905): acquireWL(4421ca18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4635): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOnTime = 1452924000000, randomSettingOnTime = 1452922419000
,D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOffTime = 1452902400000, randomSettingOffTime = 1452904782000
,D/SmartSyncScreenOnOffTimeReceiver( 4635): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightModeTurnOffOnce = false
W/BatSI   (  905): Couldn't get kernel wake lock stats
D/PMS     (  905): releaseWL(4421ca18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4806/10047)
,D/PMS     (  905): releaseWL(4425e3b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=4042
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4042:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4042
,D/PMS     (  905): acquireWL(43cb34c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{433bb198: PendingIntentRecord{424bc648 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1014027, Int=0
,D/PMS     (  905): acquireWL(42e66208): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(42e66208): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  905): acquireWL(436ca320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(43cb34c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  905): releaseWL(436ca320): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  905): acquireWL(44203be0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1387 10028 null
,D/GCM     ( 1387): Message class mow
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1387/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1387/10028)
,D/PMS     (  905): acquireWL(43da8f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(44203be0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): releaseWL(43da8f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=7 [40][3][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(426ac6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426ac6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(442d1a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1070692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(442d1a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426ca238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426ca238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43862f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43862f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44290068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1130692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44290068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44190978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(44190978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d318f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1149200, Int=0
,D/PMS     (  905): acquireWL(43d31ba0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(43d318f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4422ba88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42665668): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(43d31ba0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4422ba88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(426123c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(426123c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4716): Last usage 0, idle 1452884538s, sync interval 2592000s
I/NewsWeather( 4716): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4716): Skip sync for lookup editions
,I/NewsWeather( 4716): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4716): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1387): GoogleAccountDataService.getToken()
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1387): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1387): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/NewsWeather( 4716): Unrecoverable authentication exception
E/NewsWeather( 4716): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4716): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4716): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4716): [NET] getaddrinfo-, 1
,D/libc    ( 4716): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2471 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{42034180 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4716): [NET] getaddrinfo_proxy-, success,
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 11 3 12
,D/libc    ( 4716): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4716): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(42ab3600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1387 10028 null
,D/PMS     (  905): releaseWL(42ab3600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4716): Failed to syncNewsAppData
,E/NewsWeather( 4716): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42611ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42665668): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 622673, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1496/10028)
D/PMS     (  905): releaseWL(42611ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43622198): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43622198): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(436f3b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436f3b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(438d4240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cfade0: PendingIntentRecord{424c1b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1179273, Int=0
,D/PMS     (  905): acquireWL(442e8318): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(438d4240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4261ed20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(442e8318): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4261ed20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(431091c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1190692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(431091c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4382a178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4382a178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42b12510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42b12510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  905): acquireWL(44241a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1250691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44241a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e7b048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43e7b048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(446583a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PMS     (  905): releaseWL(446583a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4426a198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1310692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4426a198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44265928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44265928): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(44255cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/BatteryService(  905): n_update end
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(44255cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e46de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1370691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e46de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e32aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e32aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d77850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d77850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43743be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1430691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43743be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4371fb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4371fb08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4360aea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4360aea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43163538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1490691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43163538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43138758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43138758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42c89c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PMS     (  905): releaseWL(42c89c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4234aca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1550692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4234aca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42015cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42015cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41f1a5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41f1a5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(422431b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1610691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(422431b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43238b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43238b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425923c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425923c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42e85050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1670692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42e85050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425cab68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): releaseWL(425cab68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43d72460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43d72460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41e5e320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1730691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(41e5e320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425523e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(425523e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425ea0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(425ea0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4253e7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1790691, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4253e7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c73d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42c73d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(426726d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(426726d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  905): acquireWL(425ea040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1850692, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  905): Prepared write state in 31ms
,I/ProcessStatsService(  905): Prepared write state in 24ms
,D/PMS     (  905): releaseWL(425ea040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2016-01-15-04-33-00.bin
,D/PMS     (  905): acquireWL(42c73c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42c73c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44303148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(44303148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43835978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b74280: PendingIntentRecord{41b4c320 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1910691, Int=0
,D/Process (  905): killProcessQuiet, pid=4489
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  905): killProcessQuiet, pid=4157
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4489:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  905): Killing 4157:com.android.vending/u0a73 (adj 15): empty for 1821s
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  905): Recipient 4489
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(43835978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Recipient 4157
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4859): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4859): ====startRecUseTime====
D/htc.customization.log.level( 4859):  is 
W/CustomizationLogLevel( 4859): Level value is invalid, use default level 2
D/CustomizationManager( 4859):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4859): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4859): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4859): Parsing tag category name = system
I/CustomizationCIDLoader( 4859): Parsing tag category name = application
I/CustomizationCIDLoader( 4859): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4859): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4859): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4859): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4859): Parsing tag category name = Settings
D/CustomizationManager( 4859):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4859):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4859): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4859): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4859): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4859): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4859, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=4596
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4582
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=4568
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=1425
I/ActivityManager(  905): Killing 4596:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
I/ActivityManager(  905): Killing 4582:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  905): Killing 4568:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
I/ActivityManager(  905): Killing 1425:com.htc.sense.hsp/u0a53 (adj 15): empty for 1800s
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  905): killProcessQuiet, pid=3896
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  905): Killing 3896:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  905): Recipient 4568
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  905): Copying FileAsset 0x64402f18 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  905): Recipient 4582
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4596
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/dalvikvm-heap( 4195): Grow heap (frag case) to 15.214MB for 1821008-byte allocation
I/ActivityManager(  905): Recipient 1425
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/acms    ( 1895): Unregistering com.test.thalitest
E/acms    ( 1895): Could not unregister removed application com.test.thalitest
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BroadcastQueue(  905): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  905): android.os.TransactionTooLargeException
W/BroadcastQueue(  905): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  905): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  905): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  905): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  905): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  905): Recipient 3896
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3896): Died!
W/GeofencerStateMachine( 1496): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
D/PMS     (  905): acquireWL(424d03a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1496 10028 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
D/PMS     (  905): releaseWL(424d03a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PackageBroadcastService( 2225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4873 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/Parcel  ( 1256): Reading a NULL string not supported here.
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Scheme: "smsto"
I/MultiDex( 4873): install
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/MultiDex( 4873): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4873): loading existing secondary dex files
I/MultiDex( 4873): load found 1 secondary dex files
I/MultiDex( 4873): install done
I/ActivityManager(  905): Delaying start of: ServiceRecord{43e9b6c0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2225): CP2 sync disabled
I/ProviderInstaller( 4873): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 2225): doRemovePackageData com.test.thalitest
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10028, userID:0
D/PMS     (  905): acquireWL(44255cc8): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  905): releaseWL(44255cc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4891 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4891): install
I/MultiDex( 4891): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4891): loading existing secondary dex files
I/MultiDex( 4891): load found 1 secondary dex files
I/MultiDex( 4891): install done
I/ProviderInstaller( 4891): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4907 uid=10053 gids={50053, 1023, 3003, 5012}
D/Process (  905): killProcessQuiet, pid=4195
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4195:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
I/ActivityManager(  905): Recipient 4195
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageManager(  905): Unable to load service info ResolveInfo{423a8328 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4873): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4873): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5ea90
E/DriveAsyncService( 4873): disk I/O error (code 3850)
E/DriveAsyncService( 4873): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4873): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4873): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4873): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4873): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4873): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4873): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4873): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4873): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4873): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5ea90
E/DocListDatabase( 4873): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4873): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4873): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4873): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4873): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4873): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4873): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4873): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4873): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4873): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4873): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4873): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4873): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4873): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4873): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4873): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4873): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4873): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4873): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4873): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4873): threadid=1: thread exiting with uncaught exception (group=0x416f0e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4873): FATAL EXCEPTION: main
E/AndroidRuntime( 4873): Process: com.google.android.gms.drive, PID: 4873
E/AndroidRuntime( 4873): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4873): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4873): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4873): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4873): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4873): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4873): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4873): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4873): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4873): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4873): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4873): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4873): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4873): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4873): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4873): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4873): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4873): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4873): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4873): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4873): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4873): 	... 10 more
D/PluginProvider( 4907): PluginProvider onCreate
D/Process ( 4873): killProcess, pid=4873
D/Process ( 4873): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteDatabase( 4907): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4907): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4907): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4907): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4907): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4907): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4907): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4907): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4907): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4907): 	at dalvik.system.NativeStart.main(Native Method)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
W/SQLiteOpenHelper( 4907): Opened registry.db in read-only mode
D/PluginProvider( 4907): current plugin count: 19
D/HtcAppUPService( 4907): HtcUPDataProvider onCreate()
I/ActivityManager(  905): Recipient 4873
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4873) has died.
I/[PluginManager]RegisterService( 4907): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
W/[PluginManager]RegisterService( 4907): provider may killed!
W/[PluginManager]RegisterService( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4907): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4907): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4907): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4907): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4907): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4907): handle notify Blinkfeed plugin client changed
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4926 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  905): acquireWL(4427c090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4427c090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4926, uid=10073, userID:0
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/Finsky  ( 4926): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4926/10073)
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4926/10073)
D/Finsky  ( 4926): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  905): acquireWL(43f65490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41dbf2c0: PendingIntentRecord{42459a48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1732023, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{423619a0: PendingIntentRecord{425219d8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820482, Int=1800000
V/AlarmManager(  905): sending alarm PendingIntent{41ecd628: PendingIntentRecord{424bc648 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1914103, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{426342e0: PendingIntentRecord{4263d968 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452885230010, Int=900000
W/Settings( 4926): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4926): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4926): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4926): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4926): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4926): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4926): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4926): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4926): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4926): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4926): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4926): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4926): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4926): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4926): threadid=25: thread exiting with uncaught exception (group=0x416f0e30)
E/ActivityManager(  905): App crashed! Process: com.android.vending
E/AndroidRuntime( 4926): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4926): Process: com.android.vending, PID: 4926
E/AndroidRuntime( 4926): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4926): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4926): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4926): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4926): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4926): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4926): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4926): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4926): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4926): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4926): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4926, uid=10073, userID:0
D/Process ( 4926): killProcess, pid=4926
D/Process ( 4926): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2909): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4960 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2909): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2909): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64160a58
W/dalvikvm( 2909): threadid=14: thread exiting with uncaught exception (group=0x416f0e30)
E/AndroidRuntime( 2909): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2909): Process: com.google.android.googlequicksearchbox:search, PID: 2909
E/AndroidRuntime( 2909): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2909): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2909): 	at cid.d(PG:186)
E/AndroidRuntime( 2909): 	at clo.g(PG:594)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2909): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2909): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2909): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2909): 	at clr.tL(PG:827)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2909): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2909): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2909): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2909): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2909): killProcess, pid=2909
D/Process ( 2909): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4926
I/ActivityManager(  905): Process com.android.vending (pid 4926) has died.
I/ActivityManager(  905): Recipient 2909
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2909) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10476ms
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2909): Died!
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20476ms
D/WifiService(  905): Client connection lost with reason: 4
E/SQLiteDatabase( 4960): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4960): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4960): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4960): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4960): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4960): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4960): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4960): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4960): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4960): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4960): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4960): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4960): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4960): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4960): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4960): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4960): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4960): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4960): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4960): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4960): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4960): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4960): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4960): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4960): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4960): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4960): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4960): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4960): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4960): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4960): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4960): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4960): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4960): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4960): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4960): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4960): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4960): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4960): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4960): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4960): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4960): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4960): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4960): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4960): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4960): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4960): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4960): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4960): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4960): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4960): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4960): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4960): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4960): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4960): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4960): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4960): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4960): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4960): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4960): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4960): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4960): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4960): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4960): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4960): threadid=11: thread exiting with uncaught exception (group=0x416f0e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4960): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4960): Process: com.google.android.apps.docs, PID: 4960
E/AndroidRuntime( 4960): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4960): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4960): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4960): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4960): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4960): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4960): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4960): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4960): 	at aho.run(AbstractDatabaseInstance.java:455)

```
