#### Test 539786637913587_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,D/PMS     (  905): acquireWL(4347fd18): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
D/PMS     (  905): releaseWL(4347fd18): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42698d88): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/PMS     (  905): releaseWL(42698d88): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(42131180): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4421 uid=10077 gids={50077}
D/PMS     (  905): acquireWL(41dff8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{42615b50: PendingIntentRecord{42604e40 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450442828245, Int=60000
D/PMS     (  905): releaseWL(41dff8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/PMS     (  905): releaseWL(42131180): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/SMSBackup( 4421): SMSBackupAgentService started
D/SMSBackup( 4421): Checking restore status
D/SMSBackup( 4421): Restore complete
D/SMSBackup( 4421): cancelCheckAlarm
D/SMSBackup( 4421): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  905): killProcessQuiet, pid=3463
I/ActivityManager(  905): Killing 3463:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Recipient 3463
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 4419): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4419): ====startRecUseTime====
D/htc.customization.log.level( 4419):  is 
W/CustomizationLogLevel( 4419): Level value is invalid, use default level 2
D/CustomizationManager( 4419):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4419): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4419): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4419): Parsing tag category name = system
I/CustomizationCIDLoader( 4419): Parsing tag category name = application
I/CustomizationCIDLoader( 4419): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4419): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4419): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4419): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4419): Parsing tag category name = Settings
D/CustomizationManager( 4419):  Read CID file spent 0.100 (s)
D/CustomizationManager( 4419):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 4419): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4419): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4419): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4419): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4419
D/PMS     (  905): acquireHCC(423a46c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42309f88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x62e42980 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1111364816
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ba0ec8
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  905): acquireWL(41faecb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4445 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4445): Copying FileAsset 0x5c90cc90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4445): Binding Chromium to main looper Looper (main, tid 1) {41b68730}
I/LibraryLoader( 4445): Expected native library version number "",actual native library version number ""
I/chromium( 4445): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4445): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(42342490): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420c91e0:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4445): 1102581464: getState(). Returning 12
D/PMS     (  905): acquireWL(42292b00): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(42292b00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4445): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4445): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4445): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4445): Local Branch: 
I/Adreno-EGL( 4445): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4445): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4445):                  aa63bbd948f41d15fc72f585e
W/chromium( 4445): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4445): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4445): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4445): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4445): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4445): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4445): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4445): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4445): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4445): CordovaWebView is running on device made by: HTC
,W/AwContents( 4445): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1271
,W/ResourceType( 4445): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4445): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bb2588, mServedView=org.apache.cordova.engine.SystemWebView{41b781f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4445): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Enable input method client, pid=4445
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +284ms
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(41faecb0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4445): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4445): JniHelper::setJavaVM(0x41641048), pthread_self() = 1663023704
,D/JX-Cordova( 4445): jxcore cordova android initializing
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 11.559MB for 98002-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 11.642MB for 146998-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 11.762MB for 220492-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 11.942MB for 330734-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 12.199MB for 496096-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 13.212MB for 1116206-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 14.133MB for 1674304-byte allocation
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 15.558MB for 2511452-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(423a46c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42309f88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 17.646MB for 3767174-byte allocation
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=89 rxSum=68} preTxRxSum={txSum=89 rxSum=68}
D/WifiDataStallTracker(  905): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=18930 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=18931 delay=15s
D/PMS     (  905): acquireWL(42d17348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{425ddf38: PendingIntentRecord{42606928 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106283, Int=0
D/PMS     (  905): releaseWL(42d17348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/jxcore-log( 4445): Initializing JXcore engine
,W/jxcore-log( 4445): JXcore engine is ready
,W/jxcore-log( 4445): Starting JXcore engine
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:132, mTXpacketCount:131, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/jxcore-log( 4445): Platform android
W/jxcore-log( 4445): 
,W/jxcore-log( 4445): Process ARCH arm
W/jxcore-log( 4445): 
,I/SensorManager(  905): mEventCount = 1200
,I/jxcore-log( 4445): JXcore Cordova bridge is ready!
I/jxcore-log( 4445): 
,W/jxcore-log( 4445): JXcore engine is started
,D/PMS     (  905): releaseWL(42342490): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/chromium( 4445): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4445): Toggling radios to true
I/jxcore-log( 4445): 
,D/BluetoothAdapter( 4445): enable(): BT is already enabled..!
,D/WifiManager( 4445): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1348
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
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 4(ms)
D/WifiService(  905): setWifiEnabled: true pid=4445, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  905): New client listening to asynchronous messages
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4445): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4445): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4445): Radios toggled
I/jxcore-log( 4445): 
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb87e7bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
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
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): nl80211: Event message available,
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  905):    returned true
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42ca46f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=18931 mDataStallAlarmIntent=PendingIntent{42596bd8: PendingIntentRecord{42606928 android broadcastIntent}}
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/PMS     (  905): acquireWL(43676050): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:5   entry:0xb7bea338  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7bea818  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7be9fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7bea248  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7bea5b8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7bea6f0  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7bea0e8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7bea410  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb7bea4a8  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1369/10028)
D/PMS     (  905): acquireWL(4259d298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  905): acquireWL(4405ce68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/PMS     (  905): releaseWL(4259d298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/PMS     (  905): releaseWL(43676050): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,I//system/bin/ip(  364): RTNETLINK answers: No such process
D/WifiNative-wlan0(  905):    returned false
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  905): releaseWL(4405ce68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/PMS     (  905): acquireWL(440a7870): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(440a7870): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1455/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4319/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4319/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4497 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4497): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4497): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4497): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4497): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4497): Preparing secondary program dexes.
V/DexLibLoader( 4497): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4497): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4497): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4497): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4497): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4497): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4497): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4497): Dex already copied
D/OdexVerifier( 4497): Odex verification is skipped.
,V/DexLibLoader( 4497): Creating class loader
,V/DexLibLoader( 4497): Finished creating class loader
V/DexLibLoader( 4497): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4497): Dex already copied
D/OdexVerifier( 4497): Odex verification is skipped.
,V/DexLibLoader( 4497): Creating class loader
,V/DexLibLoader( 4497): Finished creating class loader
V/DexLibLoader( 4497): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4497): Dex already copied
D/OdexVerifier( 4497): Odex verification is skipped.
,V/DexLibLoader( 4497): Creating class loader
,V/DexLibLoader( 4497): Finished creating class loader
V/DexLibLoader( 4497): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4497): Dex already copied
D/OdexVerifier( 4497): Odex verification is skipped.
,V/DexLibLoader( 4497): Creating class loader
,V/DexLibLoader( 4497): Finished creating class loader
,V/DexLibLoader( 4497): Verifying classes from secondary dexes.
,D/DexLibLoader( 4497): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4497): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4497): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1162): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1162): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-88
I/wpa_supplicant( 1162): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-89
D/wpa_supplicant( 1162): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1162): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1162): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1162): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplic,ant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 1
I/wpa_supplicant( 1162): wpa_s->is_screen_on 1
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 2
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87e94e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
,I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb87e94e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb87e8718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87e8718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  905): getDiscoveryDongleList
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1162): reply (921) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-50
I/wpa_supplicant( 1162): tsf=0000000109501478
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-51
I/wpa_supplicant( 1162): tsf=0000000109501493
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-51
I/wpa_supplicant( 1162): tsf=0000000109501497
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2427
I/wpa_supplicant( 1162): level=-72
I/wpa_supplicant( 1162): tsf=0000000109501500
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-79
I/wpa_supplicant( 1162): tsf=0000000109501504
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1162): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1162): freq=2462
I/wpa_supplicant( 1162): level=-89
I/wpa_supplicant( 1162): tsf=0000000109501508
I/wpa_supplicant( 1162): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=UPC Wi-Free
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=6
I/wpa_supplicant( 1162): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1162): freq=2462
I/wpa_supplicant( 1162): level=-88
I/wpa_supplicant( 1162): tsf=0000000109501511
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC5999698
I/wpa_supplicant( 1162): ####
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 109501478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 109501493, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 109501497, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 109501500, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 109501504, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 109501508, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2462, timestamp: 109501511, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4497): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
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
D/wpa_supplicant( 1162): Add randomness: count=16 entropy=7
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1162): Get randomness: len=32 entropy=8
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87e89f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef0b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1162):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
E/FbInjectorInitializer( 4497): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
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
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(426073d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42647ae0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42647ae0 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4445): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4445): 
I/jxcore-log( 4445): my name is : HTC-HTC Desire 820_PT6605
I/jxcore-log( 4445): 
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,I/jxcore-log( 4445): attempting to connect to test coordinator
I/jxcore-log( 4445): 
,I/jxcore-log( 4445): check test folder,
I/jxcore-log( 4445): 
,W/fb4a(:<default>):StaticBindingVerifier( 4497): Verify
,I/jxcore-log( 4445): found test : ./testFindPeers.js,
I/jxcore-log( 4445): 
,I/jxcore-log( 4445): found test : ./testReConnect.js
I/jxcore-log( 4445): 
,I/jxcore-log( 4445): found test : ./testSendData.js
I/jxcore-log( 4445): 
,I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422043a8
I/PMS     (  905): Going to sleep due to screen timeout...
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/BatSI   (  905): Couldn't get kernel wake lock stats
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422043a8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423d16e0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41dab628
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,I/jxcore-log( 4445): Test app app.js loaded
I/jxcore-log( 4445): 
,I/Choreographer( 4445): Skipped 159 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4445): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4445): 
,I/chromium( 4445): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 394ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4402e448)
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4445
D/PMN     (  905): wakingUp
,D/NfcService( 1256): applyRouting -2
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/PMS     (  905): acquireWL(420cc880): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  905): releaseWL(420cc880): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/ResourceType( 4445): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4445): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b781f0 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/MtpService( 2367): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2367): [MTP][onReceive]-
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
D/PMS     (  905): acquireWL(431e94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): releaseWL(431e94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43bbd028): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  905): releaseWL(43bbd028): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=97
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1117): stop update clock
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
I/HtcPowerSaver(  905): << updateStatus
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:97 unsupport:false plugged:true
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1792): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): onScreenOn: 1450442835102
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1792): onScreenOn: 1450442835103
D/PMS     (  905): acquireWL(42729120): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
D/PMS     (  905): releaseWL(42729120): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423d16e0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423d16e0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41dab628
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(431f5150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(431f5150): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=18932 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1162): get_ip_address source addr = 02000000
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/PMS     (  905): acquireWL(43e6be70): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43e6be70): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1244): start background delete task...
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1244): size: 0 , 0
D/ContactMessageStore( 1244): Background delete complete
,D/AutoSetting( 1412): service - mHandler: cancel location update
,D/AutoSetting( 1412): service -           changes count: 0
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] getTotalRam: 1873 Mb
D/WifiService(  905): New client listening to asynchronous messages
D/PMS     (  905): acquireWL(43c99f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1792): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1792): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1792): onScreenOff
D/PMS     (  905): releaseWL(43c99f08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4497): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4497): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3268
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3268:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3268
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(434821e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,I/jxcore-log( 4445): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4445): 
D/PMS     (  905): acquireWL(4350d248): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
D/PMS     (  905): releaseWL(434821e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  905): releaseWL(4350d248): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
D/wpa_supplicant( 1162): EAPOL: disable timer tick
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4536 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
,D/AutoSetting( 1412): Util - no network available!
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1412): service - mHandler: cancel location update
D/AutoSetting( 1412): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4497): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4536): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4536): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4550 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3872
,I/ActivityManager(  905): Killing 3872:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
,I/ActivityManager(  905): Recipient 3872
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4564 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4261
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4261:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4261
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4564): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4497): Grow heap (frag case) to 9.967MB for 28144-byte allocation
W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4497): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4497): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4497): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4497): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4497): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4497): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4497): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4497): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4497): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4497): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4497): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4497): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4497): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4497): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4497): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4497): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4497): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4497): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 10.052MB for 39954-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
I/dalvikvm-heap( 4497): Grow heap (frag case) to 10.128MB for 79892-byte allocation
V/WebViewChromiumFactoryProvider( 4564): Binding Chromium to main looper Looper (main, tid 1) {41b6f258}
I/LibraryLoader( 4564): Expected native library version number "",actual native library version number ""
I/chromium( 4564): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4564): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4564): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(4318d098): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(4320ca40): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(4320ca40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4564): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4564): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4564): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4564): Local Branch: 
I/Adreno-EGL( 4564): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4564): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4564):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4564): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
,D/Process (  905): killProcessQuiet, pid=4289
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4289:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,I/ActivityManager(  905): Recipient 4289
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4497): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4602 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4310f318 u0 ReceiverList{4310f2d8 4497 com.facebook.katana/10026/u0 remote:42b90a30}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4310f318 u0 ReceiverList{4310f2d8 4497 com.facebook.katana/10026/u0 remote:42b90a30}}
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43647688 u0 ReceiverList{43647628 4497 com.facebook.katana/10026/u0 remote:43505458}}
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(442bdd90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  905): acquireWL(44207928): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4602 1000 null
,D/PMS     (  905): releaseWL(442bdd90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(44207928): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCoreFlp( 1455): Unknown pending intent to remove.
,D/SmartSyncUtils( 4602): getMobilePolicyEnabled, result = true
D/PMS     (  905): acquireWL(44207838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
D/PMS     (  905): releaseWL(44207838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1412): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  905): killProcessQuiet, pid=4319
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4319:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 4206): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4206): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 4206): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4206): Cust_ConnectToPC   : spcsc>false
,D/        ( 4206): Cust_ConnectToPC   : IPT>true
,D/        ( 4206): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4206): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4206): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4206): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4206): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4206): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4206): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4206): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4206):  defaultType:0
W/ContextImpl( 4206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
D/SmartSyncUtils( 4602): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41dab628
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41dab628, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41dab628, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41dab628
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255a7b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255a7b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4319
D/PMS     (  905): releaseWL(426073d0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  905): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  905): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/MDST    (  905): default: setTeardownRequested(true)
,D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4249c108
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
,D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
D/PMS     (  905): acquireWL(4239eb78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/PMS     (  905): acquireWL(41b60d98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(42131a10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
D/PMS     (  905): releaseWL(41b60d98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,I/CheckinService( 1223): Preparing to send checkin request
,I/EventLogService( 1223): Accumulating logs since 1450442780989
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1223): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1223): Using GMS GoogleHttpClient
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4239eb78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cbca10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 11 4 12
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4664 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4664): install
,I/MultiDex( 4664): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4664): loading existing secondary dex files
,I/MultiDex( 4664): load found 1 secondary dex files
,I/MultiDex( 4664): install done
,I/ProviderInstaller( 4664): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  905): releaseWL(42ca46f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
V/Tethering(  905): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,I/acms    ( 1895): Checking Certificates
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
D/PMS     (  905): acquireWL(424eeb00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3947/10051)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1455/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(436f3eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/PMS     (  905): releaseWL(436f3eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/PMS     (  905): releaseWL(424eeb00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10021)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(423a3b90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
D/PMS     (  905): releaseWL(423a3b90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4664/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    ( 1369): [NET] getaddrinfo-, 1
D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/PMS     (  905): acquireWL(42b22c30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10028 null
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4e9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1412): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1412): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1412): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,W/Settings( 4664): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 232
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  905): acquireWL(4265be18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,W/fb4a(:<default>):UserScope( 4497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4497): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  905): releaseWL(4265be18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,I/jxcore-log( 4445): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4445): 
,D/GCM     ( 1369): Connected
D/PMS     (  905): acquireWL(4217b5b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(42b22c30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(4217b5b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(44112bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/GCM     ( 1369): Message class mpf
I/CheckinTask( 1223): Sending checkin request (8959 bytes)
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9c4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4497): Called registerBroadcastReceiver twice.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(44112bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(43c160f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  905): releaseWL(43c160f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 216
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=5 [18][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(44066408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(44066408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d8d848 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 8 3 12
,I/CheckinTask( 1223): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1223): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  905): releaseWL(42131a10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1223): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cb52d0 that was originally bound here
E/ActivityThread( 1223): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cb52d0 that was originally bound here
E/ActivityThread( 1223): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1223): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1223): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1223): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1223): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1223): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1223): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1223): 	at bks.a(SourceFile:298)
E/ActivityThread( 1223): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1223): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1223): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1369): GCM config loaded
,D/PMS     (  905): releaseWL(4318d098): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f7e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4445): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4445): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
,E/AndroidRuntime( 4445): FATAL EXCEPTION: main
E/AndroidRuntime( 4445): Process: com.test.thalitest, PID: 4445
E/AndroidRuntime( 4445): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4445): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4445): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4445): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4445): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4445): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4445): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4445): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4445): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4445): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4445): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4445): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4445): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4445): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4445): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4445): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4445): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  905): App crashed! Process: com.test.thalitest
W/ActivityManager(  905):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  905): killProcessQuiet, pid=4335
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  905): Killing 4335:com.htc.backup/1000 (adj 15): empty #17
,D/Process ( 4445): killProcess, pid=4445
,D/Process ( 4445): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  905): Recipient 4335
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4445 uid 10348
,I/ActivityManager(  905): Recipient 4445
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{425817d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  905): Process com.test.thalitest (pid 4445) has died.
,D/WifiService(  905): Client connection lost with reason: 4
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,I/GAV2    ( 4564): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(43c3fb10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  905): acquireWL(43e1a378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1455 10028 null
,D/PMS     (  905): releaseWL(43c3fb10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(43e1a378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  905): killProcessQuiet, pid=4359
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4359:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4359
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1412): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1412): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1412): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 1
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  905): acquireWL(4390db38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=97
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4390db38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
,D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43c07730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{424a6520: PendingIntentRecord{42569508 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140404, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4400a958: PendingIntentRecord{4258c8f8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140436, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43905c68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(43c07730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  905): acquireWL(436f7ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fcab +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  905): releaseWL(436f7ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success,
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1412): service - mHandler: update timezone
,D/AutoSetting( 1412): service - handleMessage() stop self
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1412): service - handleMessage() quit looper
,D/AutoSetting( 1412): service - onDestroy() END
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cbca10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  905): releaseWL(43905c68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  905): killProcessQuiet, pid=3947
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3947:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3947
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(434cde78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434cde78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{435ee610 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43359e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/PMS     (  905): releaseWL(43359e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=98
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4306
,I/ActivityManager(  905): Killing 4306:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4306
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(426a86e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{42531870: PendingIntentRecord{428cdf38 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175854, Int=0
,D/PMS     (  905): releaseWL(426a86e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43b8c830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b8c830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43509780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43509780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42d45fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42d45fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...,
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(44103cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(44103cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=98
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(43c96cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c96cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  905): acquireWL(43496520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43496520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42bf2838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=98
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42bf2838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(440cff88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=335220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440cff88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(436da0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(436da0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=99
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1369): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1369): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1369): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1369): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1369): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1369): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cff310 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4148): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4148): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4148): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4148): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4148): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4148): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4148): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4148): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 8 3 12
,D/libc    ( 4148): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4148): [NET] getaddrinfo-,err=8
D/libc    ( 4148): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4148): [NET] getaddrinfo-, 1
,D/libc    ( 4148): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =21ca +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 272
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4148): [NET] getaddrinfo_proxy-, success
I/global  ( 4148): call createSocket() return a new socket.
D/libc    ( 4148): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4148): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4148): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4148): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(4310cca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4310cca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42601728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42601728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(440d3430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440d3430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4407bf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=455219, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4407bf90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42616a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42616a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43c46f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=515220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c46f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43dbd9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderNotification, total:0
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1594): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43dbd9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,D/TetherSettings( 4206): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4206): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4206): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4206): Cust_ConnectToPC   : spcsc>false
D/        ( 4206): Cust_ConnectToPC   : IPT>true
D/        ( 4206): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4206): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4206): Index of the first 1 = -1
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Settings( 4206): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4206): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4206): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4206): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4206): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4206): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4206): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  393): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42912ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42912ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(424ae5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=575220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424ae5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(430a6a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(430a6a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43fd7ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43fd7ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Disconnect event
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
I/wpa_supplicant( 1162): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb87e7bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplic,ant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
,D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiPerfLock(  905): release()
,D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=18933 mDataStallAlarmIntent=null
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/UsbnetStateTracker(  905): isAvailable+-
,D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/PMS     (  905): acquireWL(43b9f420): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  905): doBoolean: SET pno 1
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1162): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:4   entry:0xb7bea830  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7bea410  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7bea108  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7be9fd8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7bea5b8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(42416de0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  905): acquireWL(438f7e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  905): releaseWL(438f7e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(44065720): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1369/10028)
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
I//system/bin/ip(  364): RTNETLINK answers: No such process
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
D/PMS     (  905): releaseWL(42416de0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1162): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  905):    returned true
D/BatSI   (  905): WIFI scan started for: 450a0300 uid:1000
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/PMS     (  905): releaseWL(44065720): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
,I/Tethering(  905): No IPv4 upstream interface, giving up.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1455/10028)
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/PMS     (  905): acquireWL(440e0c48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(440e0c48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
,I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10021)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/PMS     (  905): acquireWL(44059b60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,D/PMS     (  905): acquireWL(4403f4e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
,D/PMS     (  905): releaseWL(44059b60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  905): releaseWL(4403f4e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1412): Util - no network available!
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
,D/AutoSetting( 1412): service - onCreate()
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
,D/AutoSetting( 1412): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  905): request 42461ae8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1412): service - mHandler: cancel location update
,D/AutoSetting( 1412): service -           changes count: 0
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 13.523MB for 1821008-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 15.227MB for 1821008-byte allocation
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1162): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1162): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=17 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=18 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=19 entropy=2
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1162): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1162):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1162): 2: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): No APs found - clear blacklist and try again
E/wpa_supplicant( 1162): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1162): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2d,p_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 8
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87e94e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  905): doBoolean: SET pno 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb87e94e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb87e8718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87e8718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1162): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1162): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/WifiNative-wlan0(  905):    returned false
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1162): reply (380) for get BSS: id=7
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-50
I/wpa_supplicant( 1162): tsf=0000000621674938
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=8
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-52
I/wpa_supplicant( 1162): tsf=0000000621674971
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=9
I/wpa_supplicant( 1162): bssid=9e:93:4e:3e:ba:c5,
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-79
I/wpa_supplicant( 1162): tsf=0000000621674980
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1162): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1162): ####
D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 621674938, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 621674971, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 621674980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 3 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (3) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete,
,D/wpa_supplicant( 1162): nl80211: Event message available,
D/wpa_supplicant( 1162): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Connect event
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1162): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1162): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+,
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 0
,D/HTCRequest(  905): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  905): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  905): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  905): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiStateMachine(  905): Enter handleAssociateRejectEvent
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiStateMachine(  905): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  905): Exit handleAssociateRejectEvent
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter,
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1162): nl80211: Event message available
,D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING,
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SET pno 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1162): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/BatSI   (  905): WIFI scan started for: 450a0300 uid:1000
,D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1162): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1162): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=20 entropy=3
D/wpa_supplicant( 1162): Add randomness: count=21 entropy=4
D/wpa_supplicant( 1162): Add randomness: count=22 entropy=5
D/wpa_supplicant( 1162): Add randomness: count=23 entropy=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 1162): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1162):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1162): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1162): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1162): No APs found - clear blacklist and try again
E/wpa_supplicant( 1162): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1162): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_con,nected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 0
I/wpa_supplicant( 1162): wpa_s->is_screen_on 0
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 8
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87e94e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  905): doBoolean: SET pno 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb87e94e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb87e8718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87e8718,
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1162): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1162): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  905):    returned false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1162): reply (519) for get BSS: id=7
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-50
I/wpa_supplicant( 1162): tsf=0000000626033303
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=8
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-51
I/wpa_supplicant( 1162): tsf=0000000626033343
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=9
I/wpa_supplicant( 1162): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-79
I/wpa_supplicant( 1162): tsf=0000000626033385
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1162): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=10
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2427
I/wpa_supplicant( 1162): level=-72
I/wpa_supplicant( 1162): tsf=0000000626033363
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 626033303, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 626033343, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 626033385, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 626033363, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1162): Add randomness: count=24 entropy=7
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): Get randomness: len=32 entropy=8
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:g,etSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87e89f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  905): updateConnectedAP...
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef0b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1162):    broadcast key
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1162): set send_ind_to_ndc = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1162): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79,
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  905): updateConnectedAP...,
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/WISPrService( 4206): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4206): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/WifiNative-wlan0(  905): doBoolean: SET pno 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1162): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4262edd8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42647ae0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42647ae0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  905): releaseWL(4262edd8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=25 [4][1][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
,D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
,D/WifiWatchdogStateMachine(  905): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4249c108
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WISPrService( 4206): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(42c98898): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  905): acquireWL(440dd848): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
D/PMS     (  905): acquireWL(425685b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
D/PMS     (  905): releaseWL(440dd848): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/CheckinService( 1223): Preparing to send checkin request
I/EventLogService( 1223): Accumulating logs since 1450442836414
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1223): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1223): Using GMS GoogleHttpClient
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42c98898): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{420147c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 9 4 12
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4664/10028)
,W/Settings( 4664): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4664): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4664): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4664): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4664): Local Branch: 
I/Adreno-EGL( 4664): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4664): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4664):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  905): releaseWL(43b9f420): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44115208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4536/10078)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1455/10028)
I/acms    ( 1895): Checking Certificates
I/acms    ( 1895): Checking Developer Certificates
I/acms    ( 1895): Checking Application Certificates
I/acms    ( 1895): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1895): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1895): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1895): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1895): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1895): Updating next query delay: 75600000
I/mlserverapp( 1895): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1895): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/PMS     (  905): acquireWL(440c9e90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/PMS     (  905): releaseWL(440c9e90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(44115208): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/CheckinTask( 1223): Sending checkin request (8965 bytes)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b516 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10021)
,D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4497/10026)
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/PMS     (  905): acquireWL(42a84cd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,D/PMS     (  905): releaseWL(42a84cd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
,D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =84a9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(425e4ef8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/AutoSetting( 1412): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4536): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1412): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1412): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
D/AutoSetting( 1412): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1412): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1412/10053)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4564/10151)
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 6
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4186): Grow heap (frag case) to 16.957MB for 1821008-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=14 [7][1][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4186/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1854/10178)
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  905): acquireWL(43567980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  905): releaseWL(43567980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1369): Connected
D/PMS     (  905): acquireWL(420dd818): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): acquireWL(43825550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  905): releaseWL(425e4ef8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(43825550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  905): releaseWL(420dd818): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): acquireWL(4317b7e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1369): Message class mpf
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
D/PMS     (  905): releaseWL(4317b7e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=20 [15][3][0]
D/PMS     (  905): acquireWL(4267d2f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  905): releaseWL(4267d2f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f56db0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 11 2 12
,I/CheckinTask( 1223): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1223): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(425685b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1223): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c2e598 that was originally bound here
E/ActivityThread( 1223): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c2e598 that was originally bound here
E/ActivityThread( 1223): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1223): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1223): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1223): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1223): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1223): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1223): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1223): 	at bks.a(SourceFile:298)
E/ActivityThread( 1223): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1223): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1223): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1369): GCM config loaded
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2f8a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  905): acquireWL(43085878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=635220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43085878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{440e5ce0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  905): acquireWL(43afd828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(43afd828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1412): service - mHandler: update timezone
,D/AutoSetting( 1412): service - handleMessage() stop self
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1412): service - handleMessage() quit looper
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1412): service - onDestroy() END
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1572): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1572): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bc3988 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 6 3 11
,D/PMS     (  905): acquireWL(42657c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42657c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{434e56b8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/PMS     (  905): acquireWL(436f0080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=695219, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436f0080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42a9c690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42a9c690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Process (  905): killProcessQuiet, pid=4376
,I/ActivityManager(  905): Killing 4376:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4376
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4349f2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4349f2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42645bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=755220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42645bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43826a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43826a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(44016b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41e052e8: PendingIntentRecord{424a68c0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785983, Int=0
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4805 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42616948: PendingIntentRecord{426839a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450442944447, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{435dd7f8: PendingIntentRecord{4261fad0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450443524477, Int=1800000
,D/PMS     (  905): acquireWL(42eed628): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1223 10028 null
,D/PMS     (  905): releaseWL(44016b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  905): acquireWL(436f3c08): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1223 10028 null
,D/PMS     (  905): releaseWL(42eed628): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1223): Aggregate from 1450443353385 (log), 1450441724431 (data)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4805/10047)
,D/PMS     (  905): releaseWL(436f3c08): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/Process (  905): killProcessQuiet, pid=4391
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4391:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4391
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43bca658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=815220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43bca658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43374a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43374a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(440963b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=875220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440963b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43aad678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43aad678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42570ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=935220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42570ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4402ba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4402ba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4349ee68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995219, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4349ee68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43131710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42615b60: PendingIntentRecord{426b6110 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450443664847, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{42d69ff8: PendingIntentRecord{43bb03a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450443736205, Int=0
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4602): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4602): MY_DEBUG = false
,D/SmartSyncUtils( 4602): isEpsOn(), nState = 0
,D/PMS     (  905): acquireWL(4411e4d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4602 1000 null
,D/PMS     (  905): releaseWL(43131710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4602): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4602): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4602): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4602): SettingOnTime = 1450486800000, randomSettingOnTime = 1450485502000
,D/SmartSyncScreenOnOffTimeReceiver( 4602): SettingOffTime = 1450483200000, randomSettingOffTime = 1450483319000
,W/BatSI   (  905): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4602): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4602): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4602): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(4411e4d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(440caf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440caf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(441cdb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1055220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(441cdb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41ffecd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(41ffecd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(426c8580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1115220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(426c8580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42620ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42620ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4407c328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1175220, Int=0
,D/PMS     (  905): releaseWL(4407c328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42467930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42467930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(425c48c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1235220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425c48c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42136990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42136990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(431b4cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1295220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(431b4cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4351c868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4351c868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4390f408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1355219, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4390f408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42104638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  905): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42104638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42693130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1415220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42693130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42c253d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42c253d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(440af070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1475220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(440af070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(422f48f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(422f48f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42475f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42475f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42bea5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1535220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42bea5b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(436ff5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436ff5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4229cb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4229cb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43263140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1595220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43263140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42bf2880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42bf2880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425b60b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1655220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425b60b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4379ff28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4379ff28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42592f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1715220, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42592f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(437d0e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(437d0e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43b25fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43b25fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(425ab8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1775219, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425ab8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(436cb908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(436cb908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42414bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1835219, Int=0
,I/ProcessStatsService(  905): Prepared write state in 41ms
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42414bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-41-43.bin
,D/PMS     (  905): acquireWL(432c7070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41e052e8: PendingIntentRecord{424a68c0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1519722, Int=0
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41ee98b0: PendingIntentRecord{42533058 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1530284, Int=0
,D/PMS     (  905): acquireWL(43c162f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1369 10028 null
,V/AlarmManager(  905): sending alarm PendingIntent{423b4068: PendingIntentRecord{42577a38 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820054, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{42615b60: PendingIntentRecord{426b6110 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450444564847, Int=900000
,D/PMS     (  905): releaseWL(43c162f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  905): acquireWL(440b2218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,D/PMS     (  905): acquireWL(440e63c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  905): releaseWL(440e63c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): releaseWL(440b2218): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(432c7070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(44124188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/GCM     ( 1369): Message class mow
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  905): acquireWL(44119cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  905): releaseWL(44124188): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): releaseWL(44119cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=6 [103][7][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(440c95c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(440c95c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4400c080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41dbf080: PendingIntentRecord{41dbeb58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1895220, Int=0
D/Process (  905): killProcessQuiet, pid=4148
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4148:com.android.vending/u0a73 (adj 15): empty for 1805s
,D/Process (  905): killProcessQuiet, pid=4056
,I/ActivityManager(  905): Killing 4056:com.google.android.gm/u0a107 (adj 15): empty for 1818s
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4400c080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Recipient 4056
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4148
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4841): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4841): ====startRecUseTime====
D/htc.customization.log.level( 4841):  is 
W/CustomizationLogLevel( 4841): Level value is invalid, use default level 2
D/CustomizationManager( 4841):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4841): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4841): Parsing tag category name = system
I/CustomizationCIDLoader( 4841): Parsing tag category name = application
I/CustomizationCIDLoader( 4841): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4841): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4841): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4841): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4841): Parsing tag category name = Settings
D/CustomizationManager( 4841):  Read CID file spent 0.159 (s)
D/CustomizationManager( 4841):  All configurations done spent 0.159 (s)
W/HtcNativeFlag( 4841): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4841): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4841): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4841): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4841, uid=2000 user=0
D/Process (  905): killProcessQuiet, pid=4421
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
I/ActivityManager(  905): Killing 4421:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1811s
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  905): Copying FileAsset 0x6779e560 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  905): Recipient 4421
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  905): Skipping PackageSetting{4225b5e8 com.example.hello/10356} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1572): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1572): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1455): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(41ef5b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1455 10028 null
I/acms    ( 1895): Unregistering com.test.thalitest
E/acms    ( 1895): Could not unregister removed application com.test.thalitest
D/PMS     (  905): releaseWL(41ef5b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PackageBroadcastService( 1223): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4855 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  905):   Scheme: "smsto"
I/ActivityManager(  905): Delaying start of: ServiceRecord{440af8a0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4855): install
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/MultiDex( 4855): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4855): loading existing secondary dex files
I/MultiDex( 4855): load found 1 secondary dex files
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4871 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4855): install done
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1223): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1223, uid=10028, userID:0
I/Icing   ( 1223): doRemovePackageData com.test.thalitest
D/PMS     (  905): acquireWL(4362ef90): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
I/ProviderInstaller( 4855): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4871): install
I/MultiDex( 4871): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  905): releaseWL(4362ef90): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4871): loading existing secondary dex files
I/MultiDex( 4871): load found 1 secondary dex files
I/MultiDex( 4871): install done
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4871): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1412): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  905): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1412): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4891 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4891, uid=10073, userID:0
W/PackageManager(  905): Unable to load service info ResolveInfo{425fa888 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Finsky  ( 4891): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4891/10073)
E/SQLiteLog( 4855): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4855): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca9b008
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4891/10073)
E/DriveAsyncService( 4855): disk I/O error (code 3850)
E/DriveAsyncService( 4855): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4855): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4855): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4855): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4855): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4855): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4855): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4855): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4855): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4855): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4855): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca9b008
E/DocListDatabase( 4855): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4855): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4855): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4855): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4855): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4855): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4855): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4855): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4855): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4855): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4855): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4855): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4855): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4855): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4855): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4855): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4855): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4855): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4855): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4855): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4855): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4855): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4855): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
E/AndroidRuntime( 4855): FATAL EXCEPTION: main
E/AndroidRuntime( 4855): Process: com.google.android.gms.drive, PID: 4855
E/AndroidRuntime( 4855): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4855): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4855): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4855): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4855): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4855): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4855): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4855): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4855): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4855): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4855): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4855): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4855): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4855): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4855): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4855): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4855): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4855): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4855): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4855): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4855): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4855): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4855): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4855): 	... 10 more
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
D/Process ( 4855): killProcess, pid=4855
D/Process ( 4855): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Finsky  ( 4891): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
W/Settings( 4891): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4891): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4891): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4891): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4891): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4891): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4891): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4891): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4891): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4891): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4891): threadid=25: thread exiting with uncaught exception (group=0x41739e30)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4891, uid=10073, userID:0
E/ActivityManager(  905): App crashed! Process: com.android.vending
E/AndroidRuntime( 4891): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4891): Process: com.android.vending, PID: 4891
E/AndroidRuntime( 4891): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4891): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4891): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4891): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4891): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4891): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4891): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4891): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4891): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4891): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4891): killProcess, pid=4891
D/Process ( 4891): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2901): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Recipient 4891
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.vending (pid 4891) has died.
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4931 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Recipient 4855
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4855) has died.
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
E/SQLiteLog( 2901): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2901): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63d6c060
W/dalvikvm( 2901): threadid=15: thread exiting with uncaught exception (group=0x41739e30)
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2901): killProcess, pid=2901
D/Process ( 2901): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2901): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2901): Process: com.google.android.googlequicksearchbox:search, PID: 2901
E/AndroidRuntime( 2901): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2901): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2901): 	at cid.d(PG:186)
E/AndroidRuntime( 2901): 	at clo.g(PG:594)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2901): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2901): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2901): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2901): 	at clr.tL(PG:827)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2901): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2901): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2901): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
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
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  905): Recipient 2901
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2901) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10840ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20840ms
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2901): Died!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): acquireWL(4381bf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1572): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4381bf38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
E/SQLiteDatabase( 4931): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4931): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4931): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4931): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4931): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4931): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4931): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4931): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4931): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4931): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4931): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4931): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4931): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4931): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4931): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4931): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4931): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4931): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4931): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4931): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4931): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4931): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4931): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4931): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4931): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4931): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4931): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4931): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4931): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4931): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4931): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4931): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4931): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4931): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4931): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4931): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4931): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4931): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4931): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4931): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4931): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4931): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4931): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4931): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4931): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4931): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4931): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4931): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4931): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4931): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4931): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4931): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4931): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4931): threadid=11: thread exiting with uncaught exception (group=0x41739e30)
E/AndroidRuntime( 4931): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4931): Process: com.google.android.apps.docs, PID: 4931
E/AndroidRuntime( 4931): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4931): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4931): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4931): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4931): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4931): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4931): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4931): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4931): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4931): killProcess, pid=4931
D/Process ( 4931): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4948 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4931
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4931) has died.
W/ContextImpl( 4948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4948): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4948): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4948): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4948): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4948): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4948): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4948): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4948): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4948): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4948): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4948): threadid=10: thread exiting with uncaught exception (group=0x41739e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4948): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4948): Process: com.android.keychain, PID: 4948
E/AndroidRuntime( 4948): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4948): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4948): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4948): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4948): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4948): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4948): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4948): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4948): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4961 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4948): killProcess, pid=4948
D/Process ( 4948): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450444641508.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Recipient 4948
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4948) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20477ms
D/AppTag  ( 4961): getInstance(Context context)
D/AppTag  ( 4961): getInstance(Context context)
D/AppTag  ( 4961): onCreate()
D/PMS     (  905): acquireWL(42471b48): PARTIAL_WAKE_LOCK  AsyncService 0x1 4186 10160 null
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4979 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  905): releaseWL(42471b48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bfcdd0 +
I/DeviceManagement( 4979): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4979 dbg=false s=true
I/Prism.WidgetManager( 1271): onLoadItems() +
I/DeviceManagement( 4979): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4979): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4979): WorkflowService: Starting workflow service
I/DeviceManagement( 4979): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b9cf88] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4979): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4979): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4979): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4979): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4993 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4979): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4979): SessionStateController: Checking invariants...
D/Documents( 4993): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 4993): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4993): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4993): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4993): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4993): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4993): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4993): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4993): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4993): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4993): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4993): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4993): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4993): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4993): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4993): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4993): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4993): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4993): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4993): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
E/AndroidRuntime( 4993): FATAL EXCEPTION: main
E/AndroidRuntime( 4993): Process: com.android.documentsui, PID: 4993
E/AndroidRuntime( 4993): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4993): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4993): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4993): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4993): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4993): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4993): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4993): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4993): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4993): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4993): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4993): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4993): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4993): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4993): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4993): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4993): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4993): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4993): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4993): 	... 10 more
D/Documents( 4993): Loading roots for com.android.externalstorage.documents
E/ActivityManager(  905): App crashed! Process: com.android.documentsui
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5007 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450444641827.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Err,orReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
D/Process ( 4993): killProcess, pid=4993
D/Process ( 4993): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/Process (  905): killProcessQuiet, pid=3890
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3890:com.google.android.music:main/u0a154 (adj 15): empty #17
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  905): Recipient 4993
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.documentsui (pid 4993) has died.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
D/ExternalStorage( 5007): After updating volumes, found 1 active roots
E/SQLiteDatabase( 4979): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4979): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4979): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4979): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4979): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel
```
